
/bin Directory

It is the directory where the binary files of the executable commands are located. The executable binary files of the basic commands are located under this directory.


/boot Directory

The files that are needed when the operating system is first turned on, during the loading of the kernel are located under the boot directory.


/dev Directory

The /dev directory contains the device files on the system that are recognized by Linux. Access to the disks on the system is made under this directory. For example “/dev/sda1” refers to a device. This device is a disk or a disk partition.


/etc Directory

The /etc directory is the directory that contains the configuration files on the system. It is one of the most important directories on Linux in terms of security. For example, the encrypted version of the users' passwords is kept under this directory. This file is explained later in the training.



/home Directory

The /home directory is the directory where users have various personal files. Downloaded files, documents, and user-specific files can be found under this directory. Since the files under this directory can give an idea about the user, they may be of interest to attackers in terms of security. Therefore, it is one of the directories that the SOC analyst should carefully examine. The size of this directory may vary depending on the user's activity. By default, when a new user is created, a new directory belonging to the user is created in the "/home" directory. However, because it is not mandatory, attackers do not usually create a new directory under the "/home" directory for newly created users.


/lib Directory

Under the /lib directory, there are the library files used by the executable binaries in the system.


/media Directory

The /media directory is the directory where the removable media, such as CD-ROM and USB, are mounted.


/mnt Directory

The /mnt directory is the directory where the temporarily mounted file systems are located.


/opt Directory

The /opt directory is the directory where the application software needed to be installed on the system additionally.


/proc Directory

The /proc directory is the directory that contains the files that hold information about the current status of the running processes on the system.


/root Directory

The most authorized user in Linux is the "Root" user. The root user also has a directory that contains its own files, like other users on the system. This directory is the "/root" directory. This directory can contain critical information just like any other user directory. Therefore, SOC analysts should control access to this directory separately.

The "/root" directory should not be confused with the "/" directory. The “/” directory is the topmost directory on the system. The “/root” directory is a directory under the “/” directory and belongs to the root user. Information about the root user and other users is explained in the following sections of the training.


/run Directory

The /run directory is the directory that holds information about the running system since the last boot of the system.


/sbin Directory

The /sbin directory is the directory where the binaries of executable commands are located. Usually, only the root users can run executable binaries under this directory.


/srv Directory

The /srv directory is the directory that contains the data for the services offered by the system. For example, the data of services such as TFTP or FTP are located under this directory.


/tmp Directory

The /tmp directory is the directory where temporary files are stored. Usually, the files under the "/tmp" directory are deleted during the system reboot. When analyzing a live Linux system, the cyber security specialist who responded to the incident should examine the "/tmp" directory in order to access critical data that may be deleted.


/usr Directory

The /usr directory is the directory containing executable binaries, libraries, and other files that all users of the system can access with read-only privileges.


/var Directory

The /var directory is known as the variable directory and contains system logs, files for tracking user activity, and cache files. It contains the logs that must be checked by the SOC analyst. According to the logs in the "/var" directory, the SOC analyst can see the unauthorized access to the system and take the necessary action.

In this part of the training, it is explained for what purpose each directory in the Linux file system hierarchy is used and what type of files it contains. In the next part of the training, the command line and basic commands are explained in practice.
