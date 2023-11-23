# XV Quiz (CSL 3030)

Welcome to the XV Quiz for CSL 3030 - Operating Systems!



## Instructions
- Answer the multiple-choice questions by selecting the correct option.
- For theoretical questions, provide concise and accurate explanations.
- Feel free to use this quiz for self-assessment or educational purposes.

## Multiple-Choice Questions

#### Question 1: Basics
1. What is XV6?
   - a. A programming language
   - b. A Unix-like operating system
   - c. A file system
   - d. An assembly language

#### Question 2: Architecture
2. XV6 is based on which earlier operating system?
   - a. Windows
   - b. Linux
   - c. BSD
   - d. DOS

#### Question 3: File System
3. Which file system is used in XV6?
   - a. FAT32
   - b. NTFS
   - c. ext4
   - d. simple

#### Question 4: System Calls
4. How are system calls implemented in XV6?
   - a. As functions in the C standard library
   - b. As interrupts
   - c. Through the command line
   - d. As external programs

#### Question 5: Processes
5. In XV6, what is the maximum number of processes that can run simultaneously?
   - a. 128
   - b. 256
   - c. 512
   - d. 1024

#### Question 6: Shell
6. What is the name of the shell used in XV6?
   - a. Bash
   - b. Zsh
   - c. Sh
   - d. Fish

#### Question 7: Scheduling
7. How does XV6 handle process scheduling?
   - a. Round-robin scheduling
   - b. Priority-based scheduling
   - c. First-Come-First-Serve (FCFS)
   - d. Random scheduling

#### Question 8: Memory Management
8. Which memory management technique is used in XV6?
   - a. Paging
   - b. Segmentation
   - c. Virtual Memory
   - d. None of the above

#### Question 9: Interrupts
9. How are interrupts handled in XV6?
   - a. Through polling
   - b. Using hardware interrupts
   - c. Using software interrupts
   - d. Both b and c

#### Question 10: Multithreading
10. Does XV6 support multithreading?
    - a. Yes
    - b. No

#### Bonus Question:
11. Who developed XV6?
    - a. Microsoft
    - b. Google
    - c. MIT
    - d. IBM

## Theoretical Questions

#### Question 12: Process States
12. Briefly explain the different states a process can be in within the XV6 operating system.

#### Question 13: File System Structure
13. Describe the structure of the file system in XV6. Include the key components and their roles.

#### Question 14: System Calls vs. Library Functions
14. Explain the difference between system calls and library functions in the context of XV6. Provide examples of each.

#### Question 15: Memory Paging
15. How does memory paging work in XV6? Discuss the benefits of using paging in memory management.

#### Question 16: Shell Commands
16. Name and briefly explain three essential shell commands in the XV6 operating system.

#### Question 17: Process Synchronization
17. Discuss the concept of process synchronization in XV6. Why is it essential, and what mechanisms are used to achieve it?

#### Question 18: Interrupt Handling
18. Explain the role of interrupts in the XV6 operating system. How are interrupts handled, and what is their significance in system operation?

#### Question 19: Virtual Memory
19. What is virtual memory, and how is it implemented in XV6? Discuss the advantages of using virtual memory.

#### Question 20: Boot Process
20. Outline the steps involved in the boot process of XV6. What happens from the moment the computer is powered on to when the XV6 kernel is loaded into memory?

## Answers
Please write your answers here

#### Answer 1:
b. A Unix-like operating system

#### Answer 2:
c. BSD

#### Answer 3:
d. simple

#### Answer 4:
b. As interrupts

#### Answer 5:
a. 128

#### Answer 6:
c. sh

#### Answer 7:
a. Round-robin scheduling

#### Answer 8:
a. Paging

#### Answer 9:
d. Both b and c

#### Answer 10:
b. No

#### Answer 11:
c. MIT

#### Answer 12:

In XV6, a process can be in the following states:
 - Unused: unused or terminated.
 - Embryonic : initialized.
 - Sleeping: Waiting for an event.
 - Runnable : Ready to run but waiting for CPU time.
 - Running : executing on the CPU.
 - Zombie: Terminated but have exit status information until retrieved by the parent process.

#### Answer 13

The XV6 file system has a simple structure:
- Superblock: Metadata of the file system.
- Inode: Metadata of each file or directory.
- Data blocks: Store actual file content.
- Directory structure: Maps names to inode numbers.
- File allocation table: Manages block allocation status.

#### Answer 14
In XV6:

System Calls:
Interfaces to request services from the kernel.

Examples: fork(), exec(), open().

Library Functions:
High-level routines for user-level programs.

Examples: printf(), malloc(), strcmp().

System calls interact directly with the kernel, while library functions provide abstractions built on top of system calls for easier programming


#### Answer 15
In XV6:

Memory Paging:
- memory is divided into fixed-size pages
- A page table is maintained for mapping logical address to physical address.
- Pages are brought from disk to main memory whenever there is a page fault.

Benefits:
- Non-contiguous allocation.
- Facilitates efficient use of physical memory.
- Simplifies memory management.
- Enables easy process creation.
- Provides isolation between processes.

#### Answer 16
`cd`:
Usage: cd [directory]

Description: Changes the current working directory. If no directory is specified, it changes to the user's home directory.

`ls`:
Usage: ls [options] [file(s)]

Description: Lists the contents of a directory i.e the files and the directories present in that location. Without arguments, it lists the files and directories in the current directory.

`cp`:
Usage: cp [options] source destination

Description: Copies files or directories. It can be used to duplicate files within the same directory or copy files to a different directory.

#### Answer 17


#### Answer 18

#### Answer 19

#### Answer 20

