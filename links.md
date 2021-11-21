---
layout: default
permalink: /LINKS/
---

# Links

## Week 02
1. [AWK command in Unix/Linux with examples](https://www.geeksforgeeks.org/awk-command-unixlinux-examples/)
Explains the basics of how to use the Awk command, complete with an explanation of what Awk is, what it can be used for, and examples on how to use it.

2. [MAN command in Linux with examples](https://www.geeksforgeeks.org/man-command-in-linux-with-examples/)
Explains the man command, which in my opinion is a highly underrated command that is useful for studying about any Linux commands,
especially when you don't know where to start/forget what flags you can use for the command.

3. [The Linux command line for beginners](https://ubuntu.com/tutorials/command-line-for-beginners)
In my opinion this is a very useful guide for someone who's never used/is not used to the Linux CLI before. It teaches readers the history of the Linux command line,
how to access a CLI from your computer, and also some basic commands including but not limited to file manipulation, pipes, stdout, and superuser/sudo.

4. [Bash Scripting Tutorial for Beginners](https://linuxconfig.org/bash-scripting-tutorial-for-beginners)
A short intro to shell scripting in Linux. This is quite useful for transitioning from Python scripting (which most of us are used to from DDP1) to shell scripting using sh/bash, with some
useful basic examples including one for backing up a folder into a tarball.

## Week 03
5. [An Introduction to Linux Filesystems](https://opensource.com/life/16/10/introduction-linux-filesystems)
A useful article that introduces readers to Filesystems in Linux, starting from it'sd efinition, function, directory structure, and types.

6. [Red Hat - ext4 File System Documentation](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/6/html/storage_administration_guide/ch-ext4)
Rough outline on ext4, the current primary filesystem used for most modern linux distros.

7. [The Comparison of Btrfs vs ext4 Filesystems](https://linuxhint.com/btrfs-vs-ext4-filesystems-comparison/)
A comparison between ext4 and the more modern Btrfs. Btrfs is a new CoW (copy on write) file system developed in 2009 that is starting to get more traction due to it's increased partition size and number of files.

## Week 04
8. [StackOverflow - C Memory Management](https://stackoverflow.com/questions/24891/c-memory-management/24922)
A thread discussing about how memory management works in the C programming language.

9. [CodingUnit - The functions malloc and free](https://www.codingunit.com/c-tutorial-the-functions-malloc-and-free)
This post explains about the basics of using the malloc and free command in the C programming language. In my opinion it is quite useful for learning about how C pointers relate to the malloc and free command.

10. [Programiz - C Dynamic Memory Allocation](https://www.programiz.com/c-programming/c-dynamic-memory-allocation)
Like the previous entry, this post explains about C memory allocation, but it also includes an intro on the calloc command.

## Week 05
11. [GeeksForGeeks - Copy on Write](https://www.geeksforgeeks.org/copy-on-write/)
A useful article explaining the concept of Copy on Write as a system resource management technique.

12. [javatpoint - Demand Paging](https://www.javatpoint.com/os-demand-paging)
An article explaining about Demand Paging as a concept.

13. [Tech Monitor - What is virtual memory?](https://techmonitor.ai/what-is/what-is-virtual-memory-4929986#:~:text=Virtual%20memory%20is%20a%20feature,space%20on%20the%20hard%20disk.)
This article explains about the basics of Virtual Memory in Operating Systems, and why it is implemented.

## Week 06
14. [man7.org - fork()](https://man7.org/linux/man-pages/man2/fork.2.html)
An entry on the Linux manual page about the fork function, how to use it, and it's use cases.

15. [GeeksForGeeks - fork() in C](https://www.geeksforgeeks.org/fork-system-call/)
An article that explains about C's implementation and usage of the fork() function.

16. [Wikipedia - fork (system call)](https://en.wikipedia.org/wiki/Fork_(system_call))
The Wikipedia article for fork that explains in depth about the history and variations of the fork function.

## Week 07
17. [StackOverFlow - How to use shared memory with linux in C](https://stackoverflow.com/questions/5656530/how-to-use-shared-memory-with-linux-in-c)
A StackOverFlow post discussing about how to use shared memory in Linux.
18. [man7.org - shm_overview](http://localhost:8000/faq/)
An overview on the usage of the POSIX shared memory API.
19. [tutorialspoint - Inter Process Communication - Shared Memory](https://www.tutorialspoint.com/inter_process_communication/inter_process_communication_shared_memory.htm)
An article explaining about the concept of shared memory and IPC and it's usage.

## Week 08
20. [LFS - Linux From Scratch](https://www.linuxfromscratch.org/)
The official LFS project page with step by step instructions for building an LFS system.
21. [Wikipedia - Linux From Scratch](https://en.wikipedia.org/wiki/Linux_From_Scratch)
Wikipedia article with general knowledge about LFS
22. [YouTube - Linux From Scratch 8.2](https://www.youtube.com/watch?v=5tRJgDJC7kY)
A series on how to build LFS 8.2, useful for general pointers.

## Week 09
23. [LFS - Chapter 8](https://www.linuxfromscratch.org/lfs/view/development/chapter08/chapter08.html)
Official resource on how to build the actual LFS system after setting up chroot. Alot of potential issues and warnings that may occur are covered in the guide, with any other edge cases being solvable with a quick google search.

24. [LinuxQuestions - zic: can't open sh yearistype.sh](https://www.linuxquestions.org/questions/linux-from-scratch-13/lfs-7-2-chapter-6-9-2-zic-can%27t-open-sh-yearistype-sh-4175447157/)
A forum post about a bug that may occur while setting up libstdc timezones. Apparently the enviroment variable for $TIMEZONE might get reset every so often, so be sure to set it back to /usr/share/zoneinfo. Also note that the timezone tar file included with OS212 is outdated (the one given is the a revision, while the one on the guide is a newer revision).

25. [sis.pitt.edu - What is a Makefile?](http://www.sis.pitt.edu/mbsclass/tutorial/advanced/makefile/whatis.htm#:~:text=A%20makefile%20is%20a%20special,Makefile%20depending%20upon%20the%20system).&text=These%20rules%20tell%20the%20system,recompile)%20a%20series%20of%20files.)
I was curious on what a Makefile actually is. This resource gives a clear definition of what it is and it's significance in the build process.
