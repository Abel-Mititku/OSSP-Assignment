# Main Documentation

- [Introduction](#introduction)
- ## Introduction
- Rocky Linux 9.5 in VMware Workstation 
Rocky Linux is an open-source, free, enterprise-class Linux operating system. It's a bug-for-bug 
compatible alternative to Red Hat Enterprise Linux (RHEL), intended for use in production servers and 
data centers. 
Advantages Of Rocky Linux Server: - stable: great for long-term, stable environments. - Free: the product is free and open-source. - Great for servers: good for web servers, databases, virtualization, file servers, etc. - Large community: Active development and support. - Security focused: regular updates.
- [Objectives](#objectives)
- ##Objective
- Objective 
The objective of this project is to install and configure Rocky Linux in a virtual environment, and to 
implement a system call in C that replaces the current process with a new one using the exec system 
call. This helps in understanding low-level process management and the practical use of system calls in 
Linux. 
- [Requirements](#requirements)
- ##Requirements
- Requirements: 
Hardware: - Intel/AMD CPU - 4 GB RAM - 20 GB Disk space - VMware Workstation installed 
Software: - Rocky Linux 9.5 ISO - GCC (compiler) - Basic terminal tools (vim/nano, dnf, etc.) 
- [Installation Steps](#installation-steps)
- ##Installation Steps
- 5,The file was written or edited using a Windows-based editor (like Notepad), which uses Windows- 
style line endings (\r\n). (The c file I used to execute the exec call).
- [Issues](#issues)
- ##Issues
- Issues Faced: 
1,ISO verification failed. 
2,Terminal didn’t show password while logging in. 
As I entered the required information to log in into my VM I was not able to type my password. 
3,Exec program output wasn’t showing. 
4,gcc not installed by default. (while trying to compile the c file I written to do the exec system call) 
- [Solutions](#solutions)
- [Filesystem](#filesystem)
- [Advantages and Disadvantages](#advantages-and-disadvantages)
- [Conclusion](#conclusion)
- [Future Outlook](#future-outlook)
- [Virtualization](#virtualization)
- [UNIX Standardization](#unix-standardization)

# System Call Implementation

- [Understanding System Calls](#understanding-system-calls)
- [The setpgid() System Call](#the-setpgid-system-call)
- [Implementation Process](#implementation-process)

