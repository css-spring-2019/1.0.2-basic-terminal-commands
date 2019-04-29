# Basic Terminal Commands

## Notes
- In many examples, you will see a `$` to signify that you should type the rest of the line into the terminal. You do not type the `$`.
- `# text here` -> comment (instructions, don’t type)
- `.` -> the current directory
- `..` -> the parent directory
- `~` -> home directory
- `<content>` -> Fill this in!!
- `[content]` -> This is optional

## Commands
*Note: for the following commands, you do not type the brackets, they indicate a placeholder. You do not type the $ either, that is to indicate you are on the command line.*

```sh
# change directory
$ cd [<directory>]

# list: list the contents of a directory
$ ls [-a] [-l] [<directory>]

# make directory
$ mkdir <directory>

# remove: delete a file or directory.
# CAUTION: this is irreversible!
$ rm <filename>
$ rm -rf <directory>

# use Mac's default program to open a file or folder
$ open <filename-or-directory>

# print working directory: Print the current directory
$ pwd

# copy: copy a file or directory to another directory
$ cp <filename> <directory-it-should-be-copied-to>
$ cp -R <directory> <directory-it-should-be-copied-to>

# open current working directory with Atom
$ atom .

# create a blank file if it doesn't exist
$ touch <filename>
```
