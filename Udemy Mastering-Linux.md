*Course link: https://udemy.com/course/mastering-linux
Instructors: Jannis Seemann, Denis Panjuta*
## Mastering Linux: The complete guide (71.5 hr)

### Part 1: Introduction
What exactly is Linux? 

> Linux is the **kernel** of a family of open-source Unix-like operating
> systems.

And what exactly is that??? Let's break it down:
* **OS** -> System software that manages computer hardware and provides services for computer programs. 
* **Unix** -> Multitask, multi-user OS that serves as the base for modern OS.
	* Multitasking --> Multiple programs can run simultaneously.
	* Multi-user --> Allows for multiple levels of user privilege.
* **Kernel** -> The core part of an OS, responsible for managing hardware (CPU, memory, graphics, etc.)
___
Linux distributions:
* A **distro** (distribution) is a complete package built around the Linux kernel. Each distro has its own tools, a package manager for installing software, and sometimes a desktop. 
* This course focuses on two distros:
	* **Ubuntu** -> Common and highly user-friendly. Recommended for personal use. 
	* **CentOS Stream** -> Part of the "Red Hat" family. Recommended for large scale projects and servers storing sensitive information. 
___
***Sidenote:** How installing Ubuntu turned into a 2-hour long troubleshooting session and what we learned from this experience.*

Symptoms:
* VirtualBox install of Ubuntu proceeded without issue, but running the VM caused various crashes. 
* Received errors about incompatible hypervisor and graphics display.
* Changing display settings seemed to fix issue, but VM running especially slow.
* Performance showed memory usage at steady 77-80%. 

 **Verdict:** Windows virtualization security features forcing Windows default hypervisor in between VirtualBox and hardware. Annoying, seemingly not able to disable, built into firmware. 
 **Opted to continue the course using Ubuntu through WSL instead.** 
___

CLI: `sudo apt update` -Checks for updates and downloads.
CLI: `sudo apt full-upgrade` -Installs updates. 

### Part 2: Bash and CLI
Terminal applications may looks slightly different across distros, but the structure and syntax remains the same. 
**Important**: Make sure you are using **BASH** as a default shell using the command `echo "${BASH_VERSION}"`. If no version is returned, 



### Part 3: Linux Concepts


### Part 4: Advanced Bash

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTU0NDIzNDY0MSwtMTIwNDg3MzI2MSw3NT
g0OTc2NTIsMTczODY2OTAwOCw4MTgxMTc3NzcsLTU0NjM0MzQ2
NCwtMzI2OTE1MTYxLDEwNTE0ODYzNjMsMjI2MzE0NTk4LDEwOD
E1OTU3OTYsMTkyNzE0NjM0MiwxMjg1NDgzMTU5XX0=
-->