You will often need to create/edit files and show the contents of files.
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
You can also combine both to one command: `:wq`

Use `ls -l`{{execute}} to see that your file exists.

## Bash redirection
In scripts you will often find the characters `>>` or `>`  
You can use these to redirect output to a file.

We will use these shortcuts to quickly create files:

`echo "test1" >> test1.txt`{{execute}}
`echo "test2" >> test1.txt`{{execute}}

Use `cat` to show the contents of test1.txt  
You will see that test1.text is created and `test1` and `test2` is appended to the file
 
`echo "test" > test1.txt`{{execute}}
Use `cat` to show the contents of test1.txt

You will see that the file is overwritten with `test`
