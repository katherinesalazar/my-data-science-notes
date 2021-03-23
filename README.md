03.22.21 - Command line notes
Quick Commands: https://ds.codeup.com/fundamentals/cli/intro/
	• In Finder,
command + up-arrow goes up one folder
	• pwd prints out the current working directory (where you are
	• ls (shows files and folders of your pwd & it lists the contents of a directory) short for list
	• cd (change directory, defaults to your home directory)
	• cd Desktop (changes to you Desktop if you were already in your home
directory)
	• cd ..  (navigates up a directory)
	• cd ../.. navigates up two directories
	• cd ../../..  navigates up three directories

Moving a file 
	• mv target destination
	• mv relative_path_target relative_path_destination
	• mv relative_path_target absolute_path_destination
	• Command + l = Clear content in the terminal 

https://ds.codeup.com/fundamentals/cli/overview/

Flags: 

	• If we wanted to see the contents of our current directory in "long" format, we would do the following:
			$ ls -l
			
	• -a : all filesls 
	• -l : long format
	• -h : human readable output

	• You can also use two or more flags together. For example, if you wanted to see all the files in a directory in long format, you could run:
			$ ls -l -a
	• However, short flags can be combined together, so rather than listing each flag individually you could simply type
			$ ls -la
			
	• More commands: https://www.unix.com/man-page/FreeBSD/1/ls/
	



	• Open up Visual studio code from terminal: 
		○ code ~/Desktop/test.txt

Control + C = come out of a process

Absolute and Relative File Paths
There are two ways to represent any given location within our filesystem: the absolute path, and the relative path.

You can think of these in the following way. Let's say you had a house, and you wanted to give your friend directions to the guest bedroom. You could do that in the following way:
	Starting at the front door, go up the main stairs, down the hallway to your left, and enter the last room on the right. That is the guest bedroom.

What if instead you were trying to tell them how to find the guest bathroom? It is inside the guest bedroom. You could give them all the same directions over again:
	Starting at the front door, go up the main stairs, down the hallway to your left, enter the last room on the right, and go in the first door to the right. That is the guest bathroom.

These are both examples of "absolute" paths. You are giving your friend directions to a room from a fixed point of entry in your house (the front door). Thus, you are giving them absolute directions. But what if your friend is already in the guest bedroom? Giving an absolute path then would be rather excessive. In that case, you would probably say:
	Go in the first door to the right. That is the guest bathroom.
	This is a "relative" path. You are giving your friend direction to a room relative to where they currently are.

Remember that:
• The absolute path will tell you where you are according to the root of the filesystem. It will not change, because the root of the filesystem will always be in the same place.
• The relative path will change depending on your current location. It changes because your current location within the filesystem will change as you move around it.



Windows
C:\Users\your_username
C:\Users\your_username\Desktop
Mac command line = Linux command line
Mac Folder structure
/users/your_username  is your home folder
/users/your_username/Downloads
/users/your_username/Applications
/users/your_username/Desktop
/users/your_username/Documents
/users/your_username/Desktop/examples
/users/your_username/Desktop/examples/mac_orientation.md
~ is the same as /users/your_username
~/Desktop/examples/mac_orientation.md
~/Downloads
~/Documents
~/Applications
~/codeup_data_science
~/codeup_data_science/sequel-exercises
~/codeup_data_science/python-exericses
~/codeup_data_science/python-exericses/hello.py
~/Desktop/codeup_data_science/python-exericses/hello.py
Graphical User Interface (GUI)
- has menus and icons and menus inside of menus
- with GUIs, what you see is what you get
- downside of GUIs, what you see is ALL you get
Command Line Interface (CLI)
- upside: we can run any CLI command at any time
- downside: it's not very intuitive
- incumbent on the user to learn enough CLI to do things:
    - figure out what folder you're in
    - show the contents of a folder
    - create new folders
    - move around your folder structur
    - create new files
    - move files, rename files, copy files..
In Finder,
command + up-arrow goes up one folder
pwd prints out the current working directory (where you are)
ls (shows files and folders of your pwd)
cd (change directory, defaults to your home directory)
cd Desktop (changes to you Desktop if you were already in your home
directory)
cd ..  (navigates up a directory)
cd ../.. navigates up two directories
cd ../../..  navigates up three directories
Moving a file 
mv target destination
mv relative_path_target relative_path_destination
mv relative_path_target absolute_path_destination
