man hier describes the standard Linux/Unix filesystem hierarchy.
It explains the purpose of each top-level directory and what files are typically stored there.

```
$ EXAM="LPIC 101"
$ echo 'Exam: "$EXAM"'
Exam: "$EXAM"
```

The dot `.` in a regex matches a single character

In which file is the users bash history stored? `~/.bash_history`

How would you start the editing mode after the current position of your cursor in vi? `a`

In which directory is the compiled Linux kernel normally located? `/boot`

In which file the default runlevel for a SysVInit system is set? `/etc/inittab`

Which of the following commands allows you to change the nice value of a running command? `top`

How would you extend the list of directories, where the shell is looking for executable files, with your users `~/bin` folder? `export PATH="$PATH:~/bin`

Which Environment Variable holds the language configuration for the shell? (Name only) `LANG`

Which kill signal is send by default by the kill command? (If no other supplied) -15

How can you display all environment variables? `env` `set`

Which of the following redirects the standard and error output to a file? `&>`

Which of the following are bash programs to manage jobs? jobs fg bg

Which folder generally would contain the apache2 / httpd executable on Linux? `/usr/bin`

Which partition type should an UEFI boot partition have? EF00

A regex with "a*" would match all words starting with an a? F T:`a.*`

Which command shows you the full path of a command (e.g. /bin/ls)? `which`

Which Environment Variable holds the standard editor? `EDITOR`

Which command shows you printable character sequences in an Linux executable? `strings`

Which of the following are common compression tools on Linux? `gzip` `bunzip2` `xz`

Which command allows you to print lines that match an given pattern? (Basic command only, not the variants) `grep`

Which parameter allows you to filter for devices (PCI-Bus) with lspci? `-s`

What is the maximum addressable storage space of a MBR partitioned hard disk with a 512 byte sector size? Correct, 2^32 x 512 bytes (~2TiB) is the maximum addressable storage size of MBR.

bg is an built in bash command? E.g. no regular executable. true

Which of the following files (if existing) are normally loaded during the startup of the Bourne-Again Shell (bash)? `~/.bashrc` `/etc/profile`

Which section number has the manual for the /etc/fstab file? 5

How do you power down a system in 5 minutes? `shotdown -h 5`

Which of the following are Linux filesystems and are supported directly by the Kernel? btrfs Ext4

How can you reconfigure the available languages on a Debian system? `dpkg-reconfigure locales`

How do you obtain the ip address of an network adapter in Linux? `ip address`

How do you search for modified things in the last 1 minute in the current directory? `find . -mmin -1`

Which manual shows information about the Linux filesystem hierachy? (Name of the manual page only) man hier shows the description of the Linux filesystem hierachy.

What kind of Kernel is the Linux one? monolithic kernel

# Types of Kernels and Examples
## 1. Monolithic Kernel

Most of the OS services run in kernel space: memory management, device drivers, file systems, process management.

Large and integrated kernel.

Examples:

Linux

FreeBSD, OpenBSD, NetBSD

Early Windows versions (95, 98)

MS-DOS

Commonly used in desktops, servers, and laptops.

## 2. Microkernel

Only essential services run in kernel space: IPC (inter-process communication), basic scheduling, and minimal hardware management.

Other services run in user space as separate processes.

Smaller and more modular kernel.

Examples:

QNX (real-time OS)

Minix (educational OS)

Mach (basis of early Mac OS X)

L4 family (used in embedded and secure systems)

GNU HURD (experimental)

Often used in embedded systems, real-time OS, and research.

## 3. Nanokernel

Minimalist kernel that only handles very basic tasks like interrupt handling and context switching.

Almost no OS services inside the kernel itself.

Mostly used in very specialized embedded systems or minimal RTOS.

Examples:

TinyOS (for wireless sensor networks)

Some minimal RTOS versions

Designed for extremely resource-limited or specialized hardware.
