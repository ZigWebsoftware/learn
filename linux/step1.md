It is important to know who you can navigate on a linux machine by using the command line.


## Navigating
When you start a new terminal you will be in a certain directory on the machine.  
You can see which directory this is by typing:  
`pwd`{{execute}} (PrintWorkingDirectory)

You will see that you are currently at `/root`

We can navigate to another directory with the `cd` command

Use for example `cd /`{{execute}} to navigate to the root of your machine.

## Listing contents

To see which directories/files are available in this directory you can use:
`ls`{{execute}}

We often use `ls -l`{{execute}} to get a nice list.

By default files/directories that start with a `.` are not shown.  
Add the `-a` option to show all files/directories:
`ls -la`{{execute}} 


## Fast navigation

There are some useful shortcuts to navigate.

For example
Navigate to another folder `cd usr/bin`{{execute}}

**NOTE:** 
always use your `TAB` key to autocomplete files/directories while you are typing.


If you want to return to the previous directory you can use:  
`cd -`{{execute}}

You can also navigate a directory up by using:  
`cd ..`{{execute}}

You can also quickly navigate to your user directory (the directory where we start at login) 
`cd ~`{{execute}}

