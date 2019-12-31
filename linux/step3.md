Files are not always in the correct directory, so you need to move them.
Or maybe you want to create a backup of some files.

Let's learn how to do that;


## Copy a file
Copying a file is quite easy.

Use the `cp` command to copy a file.

`cp test1.text test2.text`{{execute}} to create a copy of test1.text

Use `ls -l`{{execute}} to check that it worked.


## Move a file
First we need to create a directory, you can use `mkdir` to create one:
`mkdir my-first-folder`{{execute}}

Let's move our test2.txt into this folder:
`mv test2.text my-first-folder`{{execute}}

Use `ls -l`{{execute}} and  `ls -l my-first-folder`{{execute}} to check if the file is moved.