## Quick Summary
### A. OS Installation
I installed Rocky Linux 9.5 on VMware Workstation using a minimal setup configuration. During the process, I configured the network manually and resolved common installation issues such as the ISO checksum verification and missing dependencies. After installation, I ensured the system was updated and installed essential development tools like gcc.

### B. System Call
For the system call part, I wrote a C program that demonstrates process replacement using the execvp() function. Initially, I faced compilation errors and line-ending problems due to file formatting, but I resolved these using the dos2unix tool and by installing the necessary packages. The final program successfully executes a new process by replacing the current process image.


