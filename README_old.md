# GarageEEE_LinuxWorkshop

This introduction will provide insights into the operation of Linux. It will not explain the commands used. The commands are placed in a separate cheat sheet instead. The idea is that you should learn the commands as building-blocks, then combine them in a creative way to achieve your goals.

There are many cheat sheets online. But always try to make one for yourself, tailored for your work! We will provide our personal sheets so that you can get started right away.

Also, make your own help files or tutorials for yourself. Different sources give different examples. Some might be inspirational to you, but dull to someone else. So copy and paste links, examples, tips and tricks into your very own 'tutorial'. Someday you might share it out. But perhaps there's no need to, given the sheer number of very useful ones out there. Anyway, make your own notes.

# How to use this repository:
- just install wsl..... like hell yeah.... 
- Open the cheat sheets, copy, paste etc.
- Open the exercise file and read the instructions. Try to follow.
- read this file you are reading. This is the maintext with explanations.


# Learning Linux the "Open Every Door", "Clicking Every Button" Way

# Why Linux?
- Automation (bash scripting)
- Ease(?) of compiling libraries 
- Lot's of command line tools
- Many important downloadable hacking, scientific tools are command line!
- customizeable

# How to learn Linux: have you ever wondered how people write tutorials?
- Primary sources:
  - Linux gurus
  - Manuals/Help!

Online manuals: compare the different visual rendering and depth of explanations:

man.he.net : comprehensive (verbose?), pure ascii so hard to read!   
http://man.he.net/?topic=tar&section=all  
man7.org : comprehensive (verbose?), HTML rendering :)  
https://man7.org/linux/man-pages/man1/tar.1.html  
commandlinux.com : straight to the point, but less explanation  
https://www.commandlinux.com/man-page/man1/tar.1.html  

ss64.com : comprehensive; even has examples!  
https://ss64.com/bash/echo.html  
vs  
https://www.man7.org/linux/man-pages/man1/echo.1.html

Offline manuals: (knowing vi navigation keys helps a lot! Also, pay attention to white strip at bottom!)
```
help
help help   
help cat                #-bash: help: no help topics match `cat'.  Try `help help' or `man -k cat' or `info cat'.
man cat
info cat
```

Bash scripting  
[Advanced Bash-Scripting Guide](https://tldp.org/LDP/abs/html/)  
[Bash Reference Manual](https://www.gnu.org/software/bash/manual/bash.html)


# How to learn Linux: try out the command if you don't quite know what it means. Create test files, test folders, try it out! Just be careful not to delete important files. Always double check!

# Exploring the filesystem
root: /  
home: ~  
current directory:  .
"previous" directory / one level up:  ..

```
cd ..
cd /                  # to root
cd                    # to home
cd ~                  # to home
```
Go to home and list files, then list all files including hidden files. What do you see?
```
ls
ls -a
ls -al
```

We see several interesting 'files'
```
.
..
.bash_history

```

Try going to root, then display the folders and files there (try ls, then ls -a).

Several important folders:  
```
bin                    # do you see 'echo', 'cat', etc? Try to cat the files!
dev                    # devices
home
mnt                    # external directories, like thumbdrive or the Windows drive
var                    # your there's a folder 'log' that contains system logs
```

# Establising workflows
## downloading from github
## compiling code (C, C++)
## Installing packages
## auto backup
## auto upload to Github
## mounting, unmounting devices

