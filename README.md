# Linux useful commands

## Networking

- [Ping Host](#ping-host)
- [Get whois for domain](#get-whois-for-domain)
- [Get DNS for domain](#get-dns-for-domain)
- [Reserve loockup host](#reserve-loockup-host)
- [Outputs the webpage from url](#outputs-the-webpage-from-url)
- [Connect at host as user](#connect-to-a-host-as-a-user-ssh)

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
