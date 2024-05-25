# CSCI1670/1690: Weenix

### Overview
In Spring 2024, I developed a UNIX-based operating system kernel known as "Weenix" as part of [CSCI1670](http://cs.brown.edu/courses/cs167/content/weenix-doc.pdf) and CSCI1690 (the additional half-credit lab). This project was built during the whole semester, and more information about the overall layout and time line can be found [here](https://github.com/brown-cs1690/handout/wiki). The main components of the operating system were the following: 
- **Procs** - Introduces the basic building blocks of the Weenix operating system: threads, processes, and synchronization primitives. 
- **Drivers** - Includes the device drivers for terminals, disks, and memory devices `/dev/zero` and `/dev/null`.
- **VFS** - The virtual fie system provides a common interface between the operating system kernel and the various file systems. 
- **S5FS** - The System V File System is a file system based on the original Unix file system. 
- **VM** - Concludes the project by introducing virtual memory, where our kernel will now start managing user address spaces, running user-level code, and servicing system calls. 

DISCLAIMER: Due to the Brown Academic Code, no specific code implementation of Weenix has been included in this repository. If you are a potential employer and would like to take a look at the code, feel free to send an email to jung_ho_shin@brown.edu. 