# Termux
#### Basic commands with termux.
#### set launges: <a href="You launges has been used!">You launges has been used!</a>
---
   #### Basic commands.
   * `Ls - list of files and directories`
   * `Ls -al - formatted list with hidden directories and files`
   * `Cd dir - change directory to dir`
   * `Cd - change to home directory`
   * `Pwd - show the current Catalog`

   ---
   #### commands with files.
   * `Mkdir dir - create a dir directory`
   * `Rm file - delete the file`
   * `Rm -r dir - delete directory dir`
   * `Rm -r -f / path - delete directory dir`
   * `Rm -f file - delete a forced file`
   * `Rm -rf dir - forcibly delete the dir directory`
   * `Cp file1 file2 - copy file1 to file2`
   * `Cp -r dir1 dir2 - copy dir1 to dir2;  will create a dir2 directory if it does not exist`
   * `Mv file1 file2 - rename or move file1 to file2.  if file2 is an existing directory, move file1 to the file2 directory
   * `Ln -s file link - create a symbolic link link to the file file`
   * `Touch file - create a file`

   ---
   #### file information
   * `Cat> file - send standard input to the file`
   * `More file - output the contents of the file`
   * `Head file - print the first 10 lines of the file`
   * `Tail file - display the last 10 lines of the file`
   * `Tail -f file - output the file as it grows, starting with the last 10 lines`

   ---
   #### commands for process management`
   * `Ps - display your currently active processes`
   * `Top - show all running processes`
   * `Kill pid - kill the process with id pid`
   * `Killall proc - kill all processes named proc`
   * `Bg - list of stopped and background tasks;  continuation of the stopped task in the background`
   * `Fg - brings to the fore the last tasks`
   * `Fg n - bring task n to the forefront`
   * Eight-year file `chmod - change file rights to eight, separately for user, group and for all by adding:`
   4 - reading (r)
   2 - record (w)
   1 - execution (x)

   ---
   #### example
   * `Chmod 777 - read, write, execute for everyone`
   * `Chmod 755 - rwx for owners, rx for group and`
   Additional options: man chmod.

   ---
   #### commands for SSH

   * `Ssh user @ host - will connect to host as user`
   * `Ssh -p port user @ host - will connect to host on port port as user`
   * `Ssh-copy-id user @ host - your key to host to add login without password and by keys`

   ---
   #### search commands
   * `Grep pattern files - search for template files`
   * `Grep -r pattern dir - search recursively pattern in dir`
   * `Command |  grep pattern - look for a template in the command output`
   * `Locate file - find all files named file`

   ---
   #### system information
   * `Date - display the current date and time`
   * `Cal - display the calendar for the current month`
   * `Uptime - show the current uptime`
   * `Whoami - the name under which you are logged in`
   * `Uname -a - show kernel information`
   * `Cat / proc / cpuinfo - CPU information`
   * `Cat / proc / meminfo - memory information`
   * `Man command - show manual for command`
   * `Df - show info.  about memory of disks`
   * `Du - display the" weight "of the current directory`
   * `Free - memory usage and swap`
   * `Whereis app - possible location of the app`
   * `Which app - which program will run by default`

   ---
   #### archiving
   * `Tar cf file.tar files - create a tar archive with a file named tar.tar break files`
   * `Tar xf file.tar - unzip file.tar`
   * `Tar czf file.tar.gz files - create a tar archive with Gzip compression`
   * `Tar xzf file.tar.gz - unpack tar from Gzip`
   * `Tar cjf file.tar.bz2 - create a tar archive with Bzip2 compression`
   * `Tar xjf file.tar.bz2 - unpack tar from Bzip2`
   * `Gzip file - compress the file and rename it to file.gz`
   * `Gzip -d file.gz - expand file.gz into a file`

   ---
   #### network
   * `Ping host - ping the host and display the result`
   * `Whois domain - get whois information for the domain`
   * `Dig domain - get DNS information about the domain`
   * `Dig -x host - reverse search for a host`
   * `Wget file - download file`
   * `Wget -c file - continue stopped downloading`

   ---
   #### installing and working with packages
   * `Pkg install package - installs the package`
   * `Pkg remove package - removes the package`
   * `Pkg search package - searches the package repository`
   * `Pkg list-installed - will display a list of downloads`

   ---
   #### installation from source codes.
   * `./configure`
   * `Make`
   * `Make install`

   installation of deb packages

   * `Dpkg -i pkg.deb - install package (Debian)`

   ---
   #### commands from android
   * `Adb (Android Debug Bridge) - a utility for debugging Android devices from a PC`
   * `Pm - package manager`
   * `Pm list packages (see the list of downloaded packages)`
   * `Am - manager to start and stop applications`

   ---
   #### hotkeys
   * `Ctrl + C complete - current command`
   * `Ctrl + Z - stop the current command, continue with fg in the foreground or bg in the background`
   * `Ctrl + D - log in, the same as exit`
   * `Ctrl + W - delete one word in the current line`
   * `Ctrl + U - delete string`
   * `!!  - repeat the last command`
   * `Exit - log out`
###### by misha korzhik: report bug: misakorzik528@gmail.com
