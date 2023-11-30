# Linux Commands

![Licence](https://img.shields.io/badge/Unlicense-red)

## Overview

This list of Linux commands should provide you with a more comprehensive understanding of the tools available for various tasks in the Linux environment.

## Networking

- [Ping Host](#ping-host)
- [Get whois for domain](#get-whois-for-domain)
- [Get DNS for domain](#get-dns-for-domain)
- [Reserve loockup host](#reserve-loockup-host)
- [Outputs the webpage from url](#outputs-the-webpage-from-url)
- [Connect at host  as user](#connect-to-a-host-as-a-user-ssh)
- [Display network interfaces and their configuration](#display-network-interfaces-and-their-configuration)
- [Display active network connections](#display-active-network-connections)
- [Download a file from the internet](#download-a-file-from-the-internet)
- [Transfer files via FTP](#transfer-files-via-ftp)

## Permissions

- [Change directory permissions](#change-directory-permissions)

## File Management

- [List files and directories](#list-files-and-directories)
- [Create a new directory](#create-a-new-directory)
- [Remove a directory](#remove-a-directory)
- [Copy a file](#copy-a-file)
- [Move a file](#move-a-file)
- [Delete a file](#delete-a-file)
- [Display the contents of a file](#display-the-contents-of-a-file)

## User Management

- [Add a new user](#add-a-new-user)
- [Delete a user](#delete-a-user)
- [Change a users password](#change-a-users-password)

## System Information

- [Display system information](#display-system-information)
- [Check disk usage](#check-disk-usage)
- [Check memory usage](#check-memory-usage)
- [Display running processes](#display-running-processes)
- [Show the history of commands](#show-the-history-of-commands)

## File Compression

- [Compress a file using gzip](#compress-a-file-using-gzip)
- [Decompress a gzip file](#decompress-a-gzip-file)
- [Create a tarball archive](#create-a-tarball-archive)
- [Extract a tarball archive](#extract-a-tarball-archive)

## File and Directory Navigation

- [Change the current directory](#change-the-current-directory)
- [Go to the users home directory](#go-to-the-users-home-directory)
- [Go back to the previous directory](#go-back-to-the-previous-directory)
- [List files and directories with details](#list-files-and-directories-with-details)
- [List all files including hidden files](#list-all-files-including-hidden-files)

## Searching

- [Search for a file or directory](#search-for-a-file-or-directory)
- [Search for text within files](#search-for-text-within-files)

## Text Manipulation

- [Display the first few lines of a file](#display-the-first-few-lines-of-a-file)
- [Display the last few lines of a file](#display-the-last-few-lines-of-a-file)
- [Sort lines of a text file](#sort-lines-of-a-text-file)
- [Count words, lines, and characters in a file](#count-words-lines-and-characters-in-a-file)
- [Replace text in a file](#replace-text-in-a-file)

## System Administration

- [Shutdown the system](#shutdown-the-system)
- [Reboot the system](#reboot-the-system)
- [Display disk usage by directory](#display-disk-usage-by-directory)
- [Display the current date and time](#display-the-current-date-and-time)
- [Display the systems uptime](#display-the-systems-uptime)
- [Change the owner of a file or directory](#change-the-owner-of-a-file-or-directory)
- [Change the group ownership of a file or directory](#change-the-group-ownership-of-a-file-or-directory)
- [Schedule a command to run at a specific time using at](#schedule-a-command-to-run-at-a-specific-time-using-at)
- [Schedule a recurring command using cron](#schedule-a-recurring-command-using-cron)
- [View system logs](#view-system-logs)
- [Display the list of installed packages](#display-the-list-of-installed-packages)
- [Install a package using apt-get](#install-a-package-using-apt-get)
- [Update the package list](#update-the-package-list)
- [Upgrade installed packages](#upgrade-installed-packages)
- [Remove a package](#remove-a-package)

## SSH Key

- [Generate a new SSH key](#generate-a-new-ssh-key)
- [View your public SSH key](#view-your-public-ssh-key)

## PHP Versions

- [Switch Between Multiple PHP Versions](#switch-between-multiple-php-versions)

---


## Networking

### Ping Host

```
ping example.com
```

### Get whois for domain

```
whois example.com
```

### Get DNS for domain

```
dig example.com
```

### Reserve loockup host

```
dig -x 192.168.1.1
```

### Outputs the webpage from URL

```
curl example.com
```

### Connect to a host as a user (SSH)

```
ssh user@example.com
```

### Display network interfaces and their configuration

```
ifconfig
```

### Display active network connections

```
netstat
```

### Download a file from the internet

```
wget http://example.com/file_name
```

### Transfer files via FTP

```
ftp ftp.example.com
```



## Permissions

### Change directory permissions

```
chown -R www-data:www-data /var/www/example.com
```

```
chmod 755 /path/to/directory
```

## File Management

### List files and directories

```
ls
```

### Create a new directory

```
mkdir new_directory
```

### Remove a directory

```
rmdir directory_name
```

### Copy a file

```
cp source_file destination
```

### Move a file

```
mv source_file destination
```

### Delete a file

```
rm file_name
```

### Display the contents of a file

```
cat file_name
```

## User Management

### Add a new user

```
adduser new_username
```

### Delete a user

```
deluser username
```

### Change a users password

```
passwd username
```

## System Information

### Display system information

```
uname -a
```

### Check disk usage

```
df -h
```

### Check memory usage

```
free -h
```

### Display running processes

```
top
```

### Show the history of commands

```
history
```

## File Compression

### Compress a file using gzip

```
gzip file_name
```

### Decompress a gzip file

```
gunzip file_name.gz
```

### Create a tarball archive

```
tar -cvzf archive_name.tar.gz directory_name
```

### Extract a tarball archive

```
tar -xvzf archive_name.tar.gz
```

## File and Directory Navigation

### Change the current directory

```
cd /path/to/directory
```

## Go to the users home directory

```
cd ~
```

## Go back to the previous directory

```
cd -
```

## List files and directories with details

```
ls -l
```

## List all files including hidden files

```
ls -a
```

## Searching

### Search for a file or directory

```
find /path/to/start -name "file_name"
```

### Search for text within files

```
grep "search_text" /path/to/files/*
```

## Text Manipulation

### Display the first few lines of a file

```
head file_name
```

### Display the last few lines of a file

```
tail file_name
```

### Sort lines of a text file

```
sort file_name
```

### Count words, lines, and characters in a file

```
wc file_name
```

### Replace text in a file

```
sed 's/old_text/new_text/g' input_file > output_file
```

## System Administration

### Shutdown the system

```
shutdown -h now
```

### Reboot the system

```
reboot
```

### Display disk usage by directory

```
du -sh /path/to/directory
```

### Display the current date and time

```
date
```

### Display the systems uptime

```
uptime
```

### Change the owner of a file or directory

```
chown new_owner /path/to/file_or_directory
```

### Change the group ownership of a file or directory

```
chgrp new_group /path/to/file_or_directory
```

### Schedule a command to run at a specific time using at

```
echo "command" | at 3:00pm
```

### Schedule a recurring command using cron

```
crontab -e
```

### View system logs

```
less /var/log/syslog
```

### Display the list of installed packages

```
dpkg --list
```

### Install a package using apt-get

```
sudo apt-get install package_name
```

### Update the package list

```
sudo apt-get update
```

### Upgrade installed packages

```
sudo apt-get upgrade
```

### Remove a package

```
sudo apt-get remove package_name
```

## SSH Key

### Generate a new SSH key

**Generate a new SSH key pair (using RSA with 4096 bits)**

```
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
```

### View your public SSH key

```
cat ~/.ssh/id_rsa.pub
```

## PHP Versions

### Switch Between Multiple PHP Versions

```
sudo update-alternatives --config php
```

---

## License

This repository is unlicense[d], so feel free to fork.
