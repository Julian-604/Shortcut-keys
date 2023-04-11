# Shortcut-keys

## MOVE
use CTRL+E to move the cursor to the end of the line. `Alt+F` moves one word forward, and `Alt+B` moves one word back.

##Undo and Delete
Use `CTRL+U` to erase everything from the current cursor position to the beginning of the line. Similarly, `CTRL+K` erases everything from the current cursor position to the end of the line.


## ENG

To stop the sequence of commands when one fails, use && instead:

$ git add . && git commit -m "message" && git push origin main

##Alias frequently used commands

`alias gpom= "git push origin main"`

#HISTORY

`$ history`

`$ !121`

# Change User Type: Standard to Admin


`sudo usermod -aG sudo xxx`

# Using unmasks

I will leave you guys with one more concept that you need to be aware of (umask) that decides the default permissions for a file. Overall, the default values are:


`Umask: 0022
File: 0666
Directory: 0777
`
`https://www.redhat.com/sysadmin/introduction-chmod`

# Special permissions

Probably the most complex part of Linux permissions is the Set owner User ID (SUID), Set Group ID up on execution (SGID), and sticky bit settings. These settings allow different functions and require some experimentation to understand fully.

`SUID`: Set user ID—execute programs as another user
`SGID`: Set group ID—define group inheritance within a directory
`Sticky bit`: Load files into memory

`https://www.redhat.com/sysadmin/linux-permissions`
