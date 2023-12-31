In the Linux operating system, all filesystems are contained within one directory hierarchy. The root directory is the top level directory, and all its subdirectories make up the directory hierarchy. This differs to other operating systems such as MS-Windows which applies a separate hierarchy for each device and partition.

/bin -- binary applications (most of your executable files)

/boot -- files required to boot (such as the kernel, etc)

/dev -- your devices (everything from drives to displays)

/etc -- just about every configuration file for your system

/etc/profile.d -- contains scripts that are run by /etc/profile upon login.

/etc/rc.d -- contains a number of shell scripts that are run on bootup at different run levels. There is also typically an rc.inet1 script to set up networking (in Slackwar), an rc.modules script to load modular device drivers, and an rc.local script that can be edited to run commands desired by the administrator, along the lines of autoexec.bat in DOS.

/etc/rc.d/init.d -- contains most of the initialization scripts themselves on an rpm-based system.

/etc/rc.d/rc*.d -- where "*" is a number corresponding to the default run level. Contains files for services to be started and stopped at that run level. On rpm-based systems, these files are symbolic links to the initialization scripts themselves, which are in /etc/rc.d/init.d.

/etc/skel -- directory containing several example or skeleton initialization shells. Often contains subdirectories and files used to populate a new user's home directory.

/etc/X11 -- configuration files for the X Window system

/home -- locally stored user files and folders

/lib -- system libraries (similar to Program Files)

/lost+found -- lost and found for lost files

/media -- mounted (or loaded) devices such as cdroms, digital cameras, etc.

/mnt -- mounted file systems

/opt -- location for “optionally” installed programs

/proc -- dynamic directory including information about and listing of processes

/root -- “home” folder for the root user

/sbin -- system-only binaries (see /bin)

/sys -- contains information about the system

/tmp -- temporary files

/usr -- applications mainly for regular users

/var -- mainly logs, databases, etc.

/usr/local/bin -- the place to put your own programs. They will not be overwritten with upgrades.

/usr/share/doc -- documentation.1
