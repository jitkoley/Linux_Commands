# Basic Linux Commands

Sure, here are some basic Linux commands along with examples:

1. **`pwd` (Print Working Directory)**
   - Displays the current directory.
   ```sh
   $ pwd
   /home/user
   ```

2. **`ls` (List Directory Contents)**
   - Lists files and directories in the current directory.
   ```sh
   $ ls
   file1.txt  file2.txt  dir1  dir2
   ```
   - Lists files with detailed information.
   ```sh
   $ ls -l
   total 8
   -rw-r--r-- 1 user user  0 Jul  4 14:21 file1.txt
   -rw-r--r-- 1 user user  0 Jul  4 14:21 file2.txt
   drwxr-xr-x 2 user user 40 Jul  4 14:21 dir1
   drwxr-xr-x 2 user user 40 Jul  4 14:21 dir2
   ```

3. **`cd` (Change Directory)**
   - Changes the current directory.
   ```sh
   $ cd /path/to/directory
   ```

4. **`mkdir` (Make Directory)**
   - Creates a new directory.
   ```sh
   $ mkdir new_directory
   ```

5. **`rmdir` (Remove Directory)**
   - Removes an empty directory.
   ```sh
   $ rmdir directory_name
   ```

6. **`touch`**
   - Creates an empty file or updates the timestamp of an existing file.
   ```sh
   $ touch newfile.txt
   ```

7. **`rm` (Remove)**
   - Deletes files or directories.
   ```sh
   $ rm file.txt
   ```
   - Deletes a directory and its contents.
   ```sh
   $ rm -r directory_name
   ```

8. **`cp` (Copy)**
   - Copies files or directories.
   ```sh
   $ cp source_file destination_file
   ```
   - Copies a directory and its contents.
   ```sh
   $ cp -r source_directory destination_directory
   ```

9. **`mv` (Move)**
   - Moves or renames files or directories.
   ```sh
   $ mv old_name new_name
   ```
   - Moves a file to a different directory.
   ```sh
   $ mv file.txt /path/to/directory/
   ```

10. **`cat` (Concatenate)**
    - Displays the contents of a file.
    ```sh
    $ cat file.txt
    ```

11. **`more`**
    - Views the contents of a file one screen at a time.
    ```sh
    $ more file.txt
    ```

12. **`less`**
    - Views the contents of a file with backward and forward navigation.
    ```sh
    $ less file.txt
    ```

13. **`head`**
    - Displays the first few lines of a file.
    ```sh
    $ head file.txt
    ```

14. **`tail`**
    - Displays the last few lines of a file.
    ```sh
    $ tail file.txt
    ```
    - Follows the log file as it grows.
    ```sh
    $ tail -f logfile.txt
    ```

15. **`grep`**
    - Searches for a pattern in files.
    ```sh
    $ grep "search_term" file.txt
    ```

16. **`find`**
    - Searches for files and directories.
    ```sh
    $ find /path/to/search -name "filename"
    ```

17. **`chmod` (Change Mode)**
    - Changes file permissions.
    ```sh
    $ chmod 755 file.txt
    ```

18. **`chown` (Change Owner)**
    - Changes file owner and group.
    ```sh
    $ chown user:group file.txt
    ```

19. **`df` (Disk Free)**
    - Displays disk space usage.
    ```sh
    $ df -h
    ```

20. **`du` (Disk Usage)**
    - Displays disk usage of files and directories.
    ```sh
    $ du -sh directory_name
    ```

21. **`ps` (Process Status)**
    - Displays currently running processes.
    ```sh
    $ ps aux
    ```

22. **`top`**
    - Displays a real-time view of system processes.
    ```sh
    $ top
    ```

23. **`kill`**
    - Terminates a process.
    ```sh
    $ kill PID
    ```

24. **`ping`**
    - Checks network connectivity.
    ```sh
    $ ping google.com
    ```

25. **`wget`**
    - Downloads files from the internet.
    ```sh
    $ wget http://example.com/file.tar.gz
    ```

26. **`curl`**
    - Transfers data from or to a server.
    ```sh
    $ curl http://example.com
    ```

27. **`tar`**
    - Archives files.
    ```sh
    $ tar -cvf archive.tar file1 file2
    ```
    - Extracts an archive.
    ```sh
    $ tar -xvf archive.tar
    ```

28. **`zip`**
    - Compresses files.
    ```sh
    $ zip archive.zip file1 file2
    ```

29. **`unzip`**
    - Decompresses files.
    ```sh
    $ unzip archive.zip
    ```

30. **`ssh` (Secure Shell)**
    - Connects to a remote machine securely.
    ```sh
    $ ssh user@hostname
    ```

31. **`scp` (Secure Copy)**
    - Copies files between hosts securely.
    ```sh
    $ scp file.txt user@hostname:/path/to/destination
    ```

32. **`man` (Manual)**
    - Displays the manual page for a command.
    ```sh
    $ man ls
    ```

33. **`history`**
    - Displays command history.
    ```sh
    $ history
    ```

34. **`alias`**
    - Creates an alias for a command.
    ```sh
    $ alias ll='ls -l'
    ```

Certainly! Here are more Linux commands along with examples:

35. **`echo`**
    - Displays a line of text or a variable value.
    ```sh
    $ echo "Hello, World!"
    Hello, World!
    ```

36. **`whoami`**
    - Displays the current logged-in username.
    ```sh
    $ whoami
    user
    ```

37. **`uname`**
    - Displays system information.
    ```sh
    $ uname -a
    Linux hostname 4.15.0-20-generic #21-Ubuntu SMP Fri Apr 20 09:30:51 UTC 2018 x86_64 x86_64 x86_64 GNU/Linux
    ```

38. **`hostname`**
    - Displays or sets the system's hostname.
    ```sh
    $ hostname
    myhostname
    ```

39. **`date`**
    - Displays or sets the system date and time.
    ```sh
    $ date
    Thu Jul  4 15:30:00 UTC 2024
    ```

40. **`cal`**
    - Displays a calendar.
    ```sh
    $ cal
        July 2024
    Su Mo Tu We Th Fr Sa
        1  2  3  4  5  6
     7  8  9 10 11 12 13
    14 15 16 17 18 19 20
    21 22 23 24 25 26 27
    28 29 30 31
    ```

41. **`bc`**
    - A command-line calculator.
    ```sh
    $ echo "5 + 3" | bc
    8
    ```

42. **`xargs`**
    - Builds and executes command lines from standard input.
    ```sh
    $ echo "file1.txt file2.txt" | xargs rm
    ```

43. **`sort`**
    - Sorts lines of text files.
    ```sh
    $ sort file.txt
    ```

44. **`uniq`**
    - Reports or filters out repeated lines in a file.
    ```sh
    $ uniq file.txt
    ```

45. **`diff`**
    - Compares files line by line.
    ```sh
    $ diff file1.txt file2.txt
    ```

46. **`cmp`**
    - Compares two files byte by byte.
    ```sh
    $ cmp file1.txt file2.txt
    ```

47. **`comm`**
    - Compares two sorted files line by line.
    ```sh
    $ comm file1.txt file2.txt
    ```

48. **`awk`**
    - A powerful text processing programming language.
    ```sh
    $ awk '{print $1}' file.txt
    ```

49. **`sed`**
    - A stream editor for filtering and transforming text.
    ```sh
    $ sed 's/old_text/new_text/' file.txt
    ```

50. **`tr`**
    - Translates or deletes characters.
    ```sh
    $ echo "hello" | tr 'a-z' 'A-Z'
    HELLO
    ```

51. **`cut`**
    - Removes sections from each line of files.
    ```sh
    $ cut -d':' -f1 /etc/passwd
    ```

52. **`wc` (Word Count)**
    - Prints newline, word, and byte counts for each file.
    ```sh
    $ wc file.txt
    10  20 100 file.txt
    ```

53. **`basename`**
    - Strips directory and suffix from filenames.
    ```sh
    $ basename /path/to/file.txt
    file.txt
    ```

54. **`dirname`**
    - Strips the last component from the file name.
    ```sh
    $ dirname /path/to/file.txt
    /path/to
    ```

55. **`ln`**
    - Creates links between files.
    ```sh
    $ ln -s /path/to/original /path/to/link
    ```

56. **`file`**
    - Determines the file type.
    ```sh
    $ file file.txt
    file.txt: ASCII text
    ```

57. **`du`**
    - Estimates file space usage.
    ```sh
    $ du -h /path/to/directory
    4.0K    /path/to/directory/file1.txt
    8.0K    /path/to/directory/file2.txt
    12K     /path/to/directory
    ```

58. **`df`**
    - Reports file system disk space usage.
    ```sh
    $ df -h
    Filesystem      Size  Used Avail Use% Mounted on
    /dev/sda1        20G  5.6G   13G  30% /
    ```

59. **`mount`**
    - Mounts a file system.
    ```sh
    $ mount /dev/sda1 /mnt
    ```

60. **`umount`**
    - Unmounts a file system.
    ```sh
    $ umount /mnt
    ```

61. **`crontab`**
    - Schedules periodic jobs.
    ```sh
    $ crontab -e
    ```

62. **`at`**
    - Schedules a command to run once at a later time.
    ```sh
    $ echo "sh script.sh" | at now + 1 minute
    ```

63. **`jobs`**
    - Lists active jobs.
    ```sh
    $ jobs
    ```

64. **`fg`**
    - Brings a job to the foreground.
    ```sh
    $ fg %1
    ```

65. **`bg`**
    - Resumes a job in the background.
    ```sh
    $ bg %1
    ```

66. **`nohup`**
    - Runs a command immune to hangups, with output to a non-tty.
    ```sh
    $ nohup command &
    ```

67. **`shutdown`**
    - Brings the system down.
    ```sh
    $ sudo shutdown -h now
    ```

68. **`reboot`**
    - Reboots the system.
    ```sh
    $ sudo reboot
    ```

69. **`systemctl`**
    - Controls the systemd system and service manager.
    ```sh
    $ sudo systemctl start service
    ```

70. **`service`**
    - Runs a System V init script.
    ```sh
    $ sudo service apache2 start
    ```

71. **`useradd`**
    - Creates a new user.
    ```sh
    $ sudo useradd -m newuser
    ```

72. **`usermod`**
    - Modifies a user account.
    ```sh
    $ sudo usermod -aG groupname username
    ```

73. **`userdel`**
    - Deletes a user account.
    ```sh
    $ sudo userdel username
    ```

74. **`passwd`**
    - Changes a user's password.
    ```sh
    $ passwd
    ```

75. **`groupadd`**
    - Creates a new group.
    ```sh
    $ sudo groupadd newgroup
    ```

76. **`groupdel`**
    - Deletes a group.
    ```sh
    $ sudo groupdel groupname
    ```

77. **`groupmod`**
    - Modifies a group.
    ```sh
    $ sudo groupmod -n newgroupname oldgroupname
    ```

78. **`iptables`**
    - Administers IP packet filtering and NAT.
    ```sh
    $ sudo iptables -L
    ```

79. **`ip`**
    - Shows/manages routing, devices, policy routing, and tunnels.
    ```sh
    $ ip addr show
    ```

80. **`netstat`**
    - Prints network connections, routing tables, interface statistics, masquerade connections, and multicast memberships.
    ```sh
    $ netstat -tuln
    ```

81. **`ifconfig`**
    - Configures a network interface.
    ```sh
    $ ifconfig
    ```

82. **`ss`**
    - Another utility to investigate sockets.
    ```sh
    $ ss -tuln
    ```

83. **`scp`**
    - Secure copy (remote file copy program).
    ```sh
    $ scp file.txt user@remote_host:/path/to/destination
    ```

84. **`rsync`**
    - Remote file and directory synchronization.
    ```sh
    $ rsync -avz file.txt user@remote_host:/path/to/destination
    ```

85. **`wget`**
    - A non-interactive network downloader.
    ```sh
    $ wget http://example.com/file.tar.gz
    ```

86. **`curl`**
    - Transfers data from or to a server.
    ```sh
    $ curl http://example.com
    ```

87. **`ftp`**
    - The user interface to the ARPANET standard File Transfer Protocol.
    ```sh
    $ ftp ftp.example.com
    ```

88. **`sftp`

**
    - Secure file transfer program.
    ```sh
    $ sftp user@remote_host
    ```

89. **`nc`** (Netcat)
    - Reads and writes data across network connections using the TCP/IP protocol.
    ```sh
    $ nc -l -p 1234
    ```

90. **`telnet`**
    - User interface to the TELNET protocol.
    ```sh
    $ telnet hostname
    ```

91. **`dig`**
    - DNS lookup utility.
    ```sh
    $ dig example.com
    ```

92. **`nslookup`**
    - Queries Internet domain name servers.
    ```sh
    $ nslookup example.com
    ```

93. **`host`**
    - DNS lookup utility.
    ```sh
    $ host example.com
    ```

94. **`iptables`**
    - Administration tool for IPv4 packet filtering and NAT.
    ```sh
    $ sudo iptables -L
    ```

95. **`ufw`**
    - Uncomplicated Firewall, a front-end for iptables.
    ```sh
    $ sudo ufw enable
    ```

96. **`tcpdump`**
    - Command-line packet analyzer.
    ```sh
    $ sudo tcpdump -i eth0
    ```

97. **`wireshark`**
    - Network protocol analyzer.
    ```sh
    $ sudo wireshark
    ```

98. **`traceroute`**
    - Prints the route packets take to a network host.
    ```sh
    $ traceroute example.com
    ```

99. **`whois`**
    - Whois query program.
    ```sh
    $ whois example.com
    ```

100. **`tshark`**
    - Terminal-based network protocol analyzer.
    ```sh
    $ sudo tshark -i eth0
    ```

These commands cover a wide range of functionalities in Linux, from file management to system administration, network management, and more. Each command has many options and parameters, so it's beneficial to refer to their manual pages (`man command`) for comprehensive details.
