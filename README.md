# Multi Clipboard Automatic Messages
### Chapter 6 Project from Automate the Boring Stuff with Python

### Description
This is a python script that creates a clipboard that stores multiple messages at once. This will be useful if you do a lot of repetitive typing when responding to
emails for example. 

### Get Started
This uses the 3rd party pyperclip module which gives us access to control over the clipboard. You can install this entering 'pip install --user pyperclip' into your 
terminal. You can go in and modify the TEXT dictionary in mclip.py to include your own phrases. Each key is used as a keyphrase for quick access. You can run this file
using 'python \path-name\mclip.py \[keyphrase]' in the terminal OR by replacing \<path-name> in the batch file (mclip.bat) with your local path name, and saving the
batch file to your C:\Users\\[name] folder. You can then either run the batch file via the file explorer or press WIN+R, enter in 'mclip \[keyphrase]' and it will copy 
whichever message is associated with the given keyphrase.
Not on Windows? See https://automatetheboringstuff.com/2e/appendixb/ for a tutorial on running programs on MacOS and Linux.
