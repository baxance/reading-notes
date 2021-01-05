# Choosing a Text Editor 

##### The Basic Editors

Basic editors are the bare-bones programs that come installed on your computer. Notepad on Windows, Text Edit on Macs and Gedit or whatever comes with your flavor of Linux distro. Again, these are *basic* editors with very minimal if any features and little to no customization or extension support. They're there for you to plug in your code accurate to the letter since there's nothing to let you know if you didn't close a bracket somewhere or have a typo hidden in your code that breaks the entire website. On the plus side, if you could consider it one, such a Spartan editor *forces* you to write perfect code, and if you can't write it perfectly you're going to get pretty good at hunting for errors.

##### Third-Party Editors

These are editors developed, often for free, by developers looking to make their lives a little easier. [Visual Studio Code](https://code.visualstudio.com/), [Notepad++](https://notepad-plus-plus.org/) or [Atom](https://atom.io/), all free to download and come with slick UIs and time saving features like Code Completion which serves as an invisible hand filling out that last little keystroke you missed on, Syntax Highlighting which highlights sections of your code making it far easier to dissect at a glance, visual aids to reduce eye-strain over long sessions, and the ability to add extensions which are additional user-created aids that layer on top of the editor to fit your needs specifically. These editors are the most flexible, and as the best editor is the one that works best for you, it's good to explore these options instead of suffering through a basic editor.

##### IDEs

An IDE or *Integrated Development Environment* takes the benefits of the third party editors mentioned above and adds even more features like a file manager, compiler and a debugger. When just starting out using an IDE could be a bit overwhelming, and it's a good idea to get used to one of the third-party editors like one listed above or one of the many available online   



#### Linux Basics [1](https://ryanstutorials.net/linuxtutorial/commandline.php), [2](https://ryanstutorials.net/linuxtutorial/navigation.php), [3](https://ryanstutorials.net/linuxtutorial/aboutfiles.php)

Command Line: ls -l /home/user
- **ls** Command
- **-l /home/user** Command line Argument
    - **-l** Command line argument option to modify the behavior of the command
    
  Shell/Bash
  - The shell is the skeleton of the terminal and what causes the terminal to behave to commands you input
  - Bash is the most common shell
  - CL: Echo $SHELL displays your shell
  
  ls (list)
  - On it's own shows a listing of current location 
  - "ls [options] [location]" gives more options for the command
  - "ls -l" long listing 
  - "ls /etc" Lists specified directory, in this case directory "/etc"
  - "ls -l /etc" long listing of "/etc" directory
 
  Pathing: Aboslute or Relative
  - Absolute specifies a file/directory in relation to the **_ROOT_** or highest directory.
    -Always begins with a /
  - Relative specifies a location in relation to your current location
    -Never begins with a /
 
###### Files are Nested within each other, just like in a GUI file explorer

cd (change directory)
- Navigates you to a different directory

###### Linux ignores file extensions
  
###### Reference Sheet
  
Command | Result
-------|-------
Up/Down arrow | Scroll through command input history
PWD | Displays current working directory
~ | Shortcut to Home Directory
. | Reference to current directory
.. | Reference to parent directory
cd | On it's own returns you to home directory
Tab key | auto completion, press twice to show multiple options
         
         

[<== Back to Readme](README.md)
