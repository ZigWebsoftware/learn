You will often need to show the contents of files and edit them.
There are several ways in linux to do this.

## Showing files
To who the contents of a file we use the `cat` command.

Navigate to your user directory (`cd ~`) and show all files (`ls -la`)
You will see a file named `.bashrc`, you can view the contents of that file with:
`cat .bashrc`{{execute}}

**NOTE:** 
you don't need to navigate to a directory to show a file. 
You can always use the complete path:
`cat /root/.bashrc`


## Editing file
We will use vi to edit/create a file:
`vi test.txt`{{execute}}

The file will opened in the terminal, to start editing the file enter the key:
`i`{{execute}} (insert)

Typ some contents for you file.

When you are ready with editing you can press the key `ESC`
To save your changes you can type `:w`
To exit the the editor you type `:q`
You can also combine both to one command: `:wq`{{execute}}

Use `ls -l` to see that your file exists.
