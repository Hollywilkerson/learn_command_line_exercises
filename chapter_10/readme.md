# What is ROBOCOPY? 
Robocopy is a command that is used at the command line to make copies of files and folders.
It is also known as Robust File Copy. It comes with windows vista, but was also part
of the windows resource kit. It was made to be used for mirroring directories.

# Alternative "english" ways of asking you to copy a file:

##Can you copy the foo.txt file to slash temp? (Create foo.txt first...)
Yes you can copy the foo.txt file into the tmp directory you created. You would just type the
following in...
  
'cp foo.txt tmp'

then you will do an 'ls' command to see your options, the directory "tmp" 
should be an option then change directories into the "tmp" directory you made, by typing 
'cd tmp'
now type
'ls' 
this will list the foo.txt file copy inside the "tmp" directory. 

##Can you copy .bash_profile in your home directory to the current directory?
No I can not. I cannot find .bash_profile in my home directory.
If it were there, this would be how to copy it to my current Chapter_10 directory.
              
              Command used cp .bash_profile Chapter_10

# Do More Section
# Use the cp -r command to copy more directories with files in them.
I copied all of my desktop folders (and their files) into something/

Command used cp -r ~/desktop something


# Copy a file to your home directory or desktop.
I just reversed this command to get my something directory onto my desktop.

Command used cp -r something/ ~/desktop


# Find these files in your graphical user interface and open them in a text editor.
Using Finder, navigate to your hostname, then Desktop, then something.


