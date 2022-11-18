![The Matrix](https://images.unsplash.com/photo-1515879218367-8466d910aaa4?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1169&q=80)

# Choosing a Text Editor

Text editors help developers write code easily

## Four important features of any text editor are:

- code completion; 
- syntax highlighting; 
- variety of themes 
- extensions 

Code completion features help coders save time

Text editors help coders write HTML and CSS faster and with less errors

Syntax highlighting and themes ease eye strain

Extensions increase functionality

While you could easily go with upir computer's already embedded text editor, most developers go with third party options

# The Command Line

Terminals are key component coders must master

- Errors in the terminal slow progress
- Coder's must pay attention to detail when working in their terminals

Opening terminals are simple.  Again, most coder's choose third party options.  It's a good practice to pin it to your taskbar.

Understanding bash (Bourne again shell) helps coders know how the terminal will react to commands

Understanding and memorizing as many shortcuts as humanly possible also eases coder's lives.

## Navigation

pwd is used to find out where you're at

ls is used to show directory lists

Two important paths are *absolute* and *relative*

Absolute paths specify a location (file or directory) in relation to the root directory. You can identify them easily as they always begin with a forward slash ( / )

Relative paths specify a location (file or directory) in relation to where we currently are in the system. They will not begin with a slash.

~ (tilde) - This is a shortcut for your home directory. eg, if your home directory is /home/ryan then you could refer to the directory Documents with the path /home/ryan/Documents or ~/Documents

. (dot) - This is a reference to your current directory. eg in the example above we referred to Documents on line 4 with a relative path. It could also be written as ./Documents (Normally this extra bit is not required but in later sections we will see where it comes in handy).

.. (dotdot)- This is a reference to the parent directory. You can use this several times in a path to keep going up the hierarchy. eg if you were in the path /home/ryan you could run the command ls ../../ and this would do a listing of the root directory.

Tab is a coder's friend! it allows thought completion

## More About Files

Everything is a File

Linux is an Extensionless System

For example:

file.exe - an executable file, or program.
file.txt - a plain text file.
file.png, file.gif, file.jpg - an image.

Linux is Case Sensitive

Spaces tend to break things!

Quotes single items go in single quotes

Escape characters like \ nullifies special meaning

ls -a helps find hidden files
