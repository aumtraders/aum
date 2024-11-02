# Unix Commands Cheat Sheet

This guide provides a list of some of the most popular and widely used commands in Unix-like operating systems, including Linux and macOS.

---

## 1. File and Directory Management

- **`ls`**: Lists files and directories in the current directory.
  - `ls -l` (long format with details)
  - `ls -a` (show hidden files)

- **`cd`**: Changes the current directory.
  - Usage: `cd /path/to/directory`

- **`pwd`**: Prints the current working directory.

- **`mkdir`**: Creates a new directory.
  - Usage: `mkdir new_directory`

- **`rm`**: Deletes files or directories.
  - Usage: `rm file.txt`
  - `rm -r directory_name` (delete recursively)

- **`cp`**: Copies files or directories.
  - Usage: `cp source_file destination_file`

- **`mv`**: Moves or renames files or directories.
  - Usage: `mv old_name new_name`

---

## 2. File Content and Text Manipulation

- **`cat`**: Displays the contents of a file.
  - Usage: `cat file.txt`

- **`head`**: Shows the first few lines of a file.
  - Usage: `head -n 10 file.txt`

- **`tail`**: Shows the last few lines of a file.
  - Usage: `tail -n 10 file.txt`

- **`grep`**: Searches for a specific text pattern in files.
  - Usage: `grep "search_term" file.txt`

- **`find`**: Finds files and directories.
  - Usage: `find /path -name "*.txt"`

- **`echo`**: Displays a line of text or variables.
  - Usage: `echo "Hello, World!"`

---

## 3. Permissions and Process Management

- **`chmod`**: Changes file permissions.
  - Usage: `chmod 755 file.txt`

- **`chown`**: Changes file owner and group.
  - Usage: `chown user:group file.txt`

- **`ps`**: Displays currently running processes.
  - Usage: `ps aux`

- **`top`**: Shows real-time system processes and resource usage.

- **`kill`**: Ends a process by its process ID.
  - Usage: `kill 1234`

---

## 4. Networking and System Information

- **`ping`**: Checks the network connection to a host.
  - Usage: `ping google.com`

- **`ifconfig`** or **`ip`**: Shows network interface configurations.

- **`netstat`**: Displays network connections, routing tables, and more.

- **`curl`**: Transfers data from or to a server (used for APIs or downloading files).
  - Usage: `curl https://example.com`

- **`wget`**: Downloads files from the internet.
  - Usage: `wget https://example.com/file.zip`

---

## 5. System and Disk Usage

- **`df`**: Shows disk space usage of file systems.
  - `df -h` (human-readable format)

- **`du`**: Checks the disk usage of files and directories.
  - Usage: `du -h /path/to/directory`

- **`free`**: Displays memory usage.
  - `free -m` (in megabytes)

---

## 6. Archiving and Compression

- **`tar`**: Archives multiple files into one file.
  - Create archive: `tar -cvf archive.tar file1 file2`
  - Extract archive: `tar -xvf archive.tar`

- **`zip`**: Compresses files into a `.zip` archive.
  - Usage: `zip archive.zip file1 file2`

- **`unzip`**: Extracts files from a `.zip` archive.
  - Usage: `unzip archive.zip`

---

## 7. User and Group Management

- **`whoami`**: Displays the current user’s username.

- **`id`**: Shows user identity information.

- **`sudo`**: Executes a command with superuser privileges.
  - Usage: `sudo apt-get update`

- **`adduser`** / **`useradd`**: Creates a new user.

- **`passwd`**: Changes a user’s password.

---

## 8. Shell Scripting and Automation

- **`alias`**: Creates shortcuts for commands.
  - Usage: `alias ll="ls -l"`

- **`cron`**: Sets up scheduled tasks (cron jobs).
  - Edit cron jobs: `crontab -e`

- **`env`**: Shows or sets environment variables.

---

Use this guide to help navigate and utilize Unix commands more efficiently!
