# LS Command Guide


The `ls` command in Unix and Unix-like operating systems is used to list directory contents. Below are some commonly used variations of the `ls` command. For more detailed information, refer to the [Documentation](https://www.gnu.org/software/coreutils/manual/coreutils.html#ls-invocation).

## Basic Command

- `ls`: List files and directories in the current directory.

## Showing Hidden Files

- `ls -a`: List all files and directories, including hidden ones (those starting with a dot `.`).

## Long Format Listing

- `ls -l`: List with detailed information like permissions, owner, size, and modification time.

## Combined Long Format and Hidden Files

- `ls -la`: Combines `-l` and `-a` flags to show detailed information of all files, including hidden ones.

## Human-Readable File Sizes

- `ls -lh`: List with detailed information, with file sizes in a human-readable format (e.g., KB, MB).

## Sorting by File Size

- `ls -lS`: List with detailed information, sorted by file size.

## Listing a Specific Directory

- `ls [directory]`: List files and directories in the specified directory.
  - Example: `ls /usr/local/bin`

## Recursive Listing

- `ls -R`: List all files in the directory and its subdirectories recursively.

## Sorting by Modification Time

- `ls -t`: List files and directories sorted by time of last modification.

## Color-Coded Listing

- `ls --color`: List files and directories with color-coded output, which helps to distinguish different file types.

For more examples and usage, you can also visit the [Linux ls command tutorial](https://www.howtogeek.com/448446/how-to-use-the-ls-command-on-linux/).
