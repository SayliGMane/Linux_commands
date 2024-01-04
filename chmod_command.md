# Command  `chmod`
  `chmod`` - change file mode bits

 ## Description: 

   > `chmod` changes the file mode bits of each given file according to mode.

   > `chmod` lets you change the permissions of a file or directory to all types of users.

 ## Two Operations you can perform with `chmod` Command: 

   > User Level permissions.

   > File Level permissions.   

 ## The syntax for the `chmod` command in Linux:

  - chmod [OPTION]... MODE[,MODE]... FILE...
  - chmod [OPTION]... OCTAL-MODE FILE...
  - chmod [OPTION]... --reference=RFILE FILE..
`

 ## Options Available in `chmod` Command:
 
  - `-f` : supress all error messages.
  - `-R` : change files and directories recursively

## Examples

Examples of Using the Symbolic mode:
>Read, write and execute permissions to the file owner:
    `chmod u+rwx [file_name]`

>Remove write permission for the group and others:
     `chmod go-w [file_name]`

>Read and write for Owner, and Read-only for the group and other:
    `chmod u+rw,go+r [file_name]``



 ## Reference:

  - [Geek](https://www.geeksforgeeks.org/chmod-command-linux/?ref=header_search)
  - man chmod
  - chmod --help

