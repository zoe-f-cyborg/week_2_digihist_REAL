This week definitely gave me more trouble than previously. I felt pretty overshelmed by Wget and couldn't see the point of it yet, so it made it slow going to get me motivated to work on it. Discord's "search" function was invaluable in helping me get through certain spots, as well as the live assistance of both the professor and other students. 

### Anaconda 

I have downloaded this software before for another class (though I was on a different laptop at the time),
so I was (somewhat) familiar with it.

It did take me a shamefully long time to figure out how to access the command line, but I eventually got it. 

### Wget

A tale of woe and perserverance, in 2 parts: 

#### Part 1: Homebrew

- the ask for a passwrod to install homebrew briefly had me stumped, until I realized it was the password for my laptop itself (not something specific to python).
- I got this message after my first attempt at installing: 
``` 
Error downloading Command Line Tools for Xcode: The operation couldn’t be completed. (PKDownloadError error 8.) 
Done.
Error downloading updates.
==> /usr/bin/sudo /bin/rm -f /tmp/.com.apple.dt.CommandLineTools.installondemand.in-progress
==> /usr/bin/sudo /usr/bin/xcode-select --switch /Library/Developer/CommandLineTools
xcode-select: error: invalid developer directory '/Library/Developer/CommandLineTools'
Failed during: /usr/bin/sudo /usr/bin/xcode-select --switch /Library/Developer/CommandLineTools
``` 

I went to [this](https://treehouse.github.io/installation-guides/mac/homebrew) website, which told me to 
download "Xcode" from the apple app store. I did, and then the homebrew installation worked. 

#### Part 2: Sublime Text

I hadn't intalled this yet so I felt quite lost, since there was nothing on the website specifically telling us how to set it up. I tried to follow [this](https://docs.anaconda.com/anaconda/user-guide/tasks/integration/sublime/) tutorial but then got stuck at the point when you're supposed to search "conda" in the command palette-- "conda" was not showing up when I searched it. I fell into a bit of a rabbit hole trying to figure out how to use anaconda, then python, and eventually I moved on to the next section as I was already a few days behind and wanted to get through this week's material. 

UPDATE: So I asked on discord about where my problem might be, since sublime seems unavoidable, and they really helped me figure out what I was doing (shoutout to cocochantal)! I realize now that sublime doesn't need to be linked up to any other application, it's just a basic sort of tool, and all you do to make it a python file is save it as .py and invoke it with "python" in the command line. My real problem was not understanding how to navigate the directories properly, and being generally unfamiliar with coding language. 

### APIs -- Json

Once I had a better grasp of how to use the terminal and sublime text, this task was much easier. I was able to make the file and save it as a table and open it in "numbers," as well as save it as a permalink [here](https://json-csv.com/c/Yte9). 

### OCRs -- R Script 

I tried launching it several times and nothing happened. I looked more closely at the image on the instructions page and saw it was using a different version (1.456) form the one it automatically chose when I installed anaconda. After downloading the correct version, I attempted to run the code provided, I got a long error including this messgae for tesseract: 

![screenshot](error2.png)

And this for magick:

![screenshot](error3.png) 

I asked for help in Discord and eventually just dowloaded R-studio independent of anaconda. (I will probably have to delete the other version as my computer's storage has been filling up.) Once I re-opened the r-script I had already started, there was a small yellow banner saying `packages, magick, magrittr, and tesseract required but are not installed. Install Don't Show Again`. I was tempted to click but slightly afraid I would screw something up, so just clicked "run" again. 

The code ran, and I was able to OCR the file!

![success](ocr-success.png)

To make sure I had a basic grasp on how the code works, I tried to ocr a different file, just by changing the name of the .jpg from ending on "30" to ending in "35" 

This is the original:

![og](e001518035.jpg)

And this is the OCRed version:

![ocr2](ocr-2.png) 

Not as pretty/succesful, but *something* happened, so I consider it a success. 

### Conclusion

This week's programs definitely presented a challenge for me. There were moments (mostly with wget) where I felt overwhelmed and frustrated and just wanted to turn in the towel on the whole week's work. I'm still a bit anxious about falling behind in this course, so did rush through some of the programs after wget faster than I would have liked (curse on my past self for thinking two summer classes + working part time was a good idea), but I think I ended up setting a foundation that I can return to if I choose (and if it is relevant to later parts of the course). 

I also found I slowed down whenever I returned to this journal folder and sometimes got sidetracked trying to make this file look decent (for example, I taught myself how to upload images into my repo and display them in .md folders today). This week's journal was partially live, because I was not sure at exactly which point I would have to turn in the towel. I constantly wrote and then overwrote some variation on "this is where I gave up." Simply doing this was often helpful in making me *not want* to give up and clarifying that the issue wasn't insurmountable. Although it sometimes slowed me down, it also provides a history of my struggles and what helped, and so will hopefully serve as a resource to myself in the future if/when I return to these programs. 
