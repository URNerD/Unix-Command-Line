# Working on the Unix Command Line

The Unix (or UNIX if you insist) **shell** is the program that interprets commands you type when you are working on the "command line." On Unix the shell is just another program, and many people have written shells over the years. The most commonly used shell on Mac OS X is called **bash** (the Bourne again shell, most Unix shells pay homage to the orginal shell, **sh** by ending their names in _sh_).

The shell lets you know it is waiting for input buy printing a prompt – shells based on the original Bourne shell, including **bash** include a dollar sign '$' in the prompt.

## Navigating the file system

### Unix file system concepts

The slash character (/) is used as the path seperator.

The terms _directory_ and _folder_ are synonymous.

A directory is nothing more than a special type of file that acts as an index to the file system. Each directory has two sepecial entries '.' and '..' (dot and dot dot). They refer to the current directory and its parent directory - they are very handy short cuts.

### Commands

cd - change directory 

pwd - print working directory

ls - list directory

mv - move (rename) a file

cp - copy a file 

rm - remove (delete) a file

mkdir - make directory

rmdir - remove directory

## Viewing files

cat - concatenate files

less - page through a file (child of more)

grep - look for patterns in a file

## Editing files

vi - visual editor

cursor is the arrow keys or h, j, k, l for up, down, left, right
o - open a line below the cursor
O - open a line above the cursor
a - append after the cursor
i - insert before the cursor
x - delete the character under the cursor
esc - exit insert mode (return to command mode)
: - begin a "long" command, for example :wq to write your file and quit. Use :q! to abandon your changes.
