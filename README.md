# dailyreportjashan
# Daily Report :

# DAY 1  :   
On the first day of training, Mam Priyanka introduced us to the faculty members of our department. After that, the Head of Department (HOD) gave us an overview of the upcoming projects, along with the rules and guidelines we need to follow. She also explained the subjects we will be studying in the next semester and the specialization options available for the fifth and sixth semesters.

Next, we attended a training session that lasted about three hours. Mam Priyanka introduced the first topic: Fundamentals of Linux. She shared the history of Linux, explained its various uses, and talked about companies that use Linux, including product-based companies, service-based companies, and startups. She also explained the differences between Linux and Windows, highlighting why Linux can be a better choice. Finally, she discussed the career opportunities in this field.

After that, we learned about the booting process and its different types.

**INSTALLATION OF LINUX**  
We installed Linux on our laptops. For this, we downloaded Oracle VirtualBox version 7.1.10 and Ubuntu (Linux) version 24.04.2.

# DAY 2 :  
On the second day, we started by reviewing the topics covered on the first day.

We then began learning about the **KERNEL**, which is the core part of an operating system responsible for managing system resources and handling communication between hardware and software. After that, we studied the shell, which acts as the interface between the user and the kernel. Mam Priyanka explained these concepts clearly using a diagram.

We also covered four types of shells: sh, bash, csh, and ksh, and discussed two categories of shells: command-line shells and graphical shells. Additionally, we explored the Linux file system structure.

# COMMANDS  
We practiced several Linux commands such as ls, date, mkdir, whereis, whatis, cat, cp, cd, and others. Here are some commands with their descriptions:

| Command | Description                              |
|---------|----------------------------------------|
| ls      | Lists files and directories            |
| date    | Displays the current date and time     |
| whereis | Locates the binary, source, and manual files |
| whatis  | Provides a brief description of commands |
| mkdir   | Creates a new directory                 |
| pwd     | Shows the current directory path       |
| mv      | Moves or renames files/directories     |
| cd      | Changes the current directory           |
| cp      | Copies files or directories             |
| whoami  | Displays the username currently logged in |
| cat     | Displays the contents of a file         |
| touch   | Creates an empty file or updates the timestamp |

# DAY 3  :  
We began day 3 by revisiting key concepts from the previous days:

# 🖥️ Dual Boot  
- Dual booting allows a computer to run two different operating systems.  
- When the computer starts, the user can choose which OS to boot.  
- A common setup is dual booting Windows and Linux.

# 📀 ISO File  
- An ISO file is a disk image that contains all the data from a CD, DVD, or other media.  
- ISO files are often used to distribute Linux distributions and other bootable software.

# 🧱 Bare Metal Installation  
- Installing an operating system directly on physical hardware without virtualization is called bare metal installation.  
- It provides direct access to hardware resources.

# 💼 VMware  
- VMware is commercial virtualization software used primarily in enterprise environments.  
- It offers high performance and professional support.

# 🔧 VirtualBox  
- VirtualBox is free and open-source virtualization software developed by Oracle.  
- It is ideal for personal use, development, and testing.

# 🗂️ Partitioning Schemes  
- Partitioning divides a hard disk into separate sections called partitions.  
- Each partition can have its own file system or operating system.

Common partitioning schemes include:  
- MBR (Master Boot Record) – older system supporting up to 4 primary partitions, used with BIOS systems.  
- GPT (GUID Partition Table) – modern standard supporting more partitions, compatible with UEFI systems.

# 🔐 File and Directory Permissions in Linux  
- Linux controls access to files and directories through permissions.  
- The `chmod` command is used to change these permissions.  
- Syntax: `chmod [who][operator][permission] [file]`

Details:  
- **Who:**  
  - u = user (file owner)  
  - g = group  
  - o = others  
  - a = all (user + group + others)  
- **Operator:**  
  - + to add permission  
  - - to remove permission  
  - = to set exact permission  
- **Permission:**  
  - r = read  
  - w = write  
  - x = execute  

# 🔁 Redirection in Linux  
Redirection lets you send command input or output to files or other commands instead of the terminal.

**Output Redirection**

| Type    | Symbol | Example                     | Description                           |
|---------|--------|-----------------------------|-------------------------------------|
| Output  | >      | `echo "Hello" > file.txt`    | Writes "Hello" to file.txt (overwrites existing content) |
| Append  | >>     | `echo "World" >> file.txt`   | Adds "World" to the end of file.txt |

**Input Redirection**

| Type  | Symbol | Example                  | Description                      |
|-------|--------|--------------------------|----------------------------------|
| Input | <      | `wc -l < file.txt`        | Uses file.txt as input for wc -l |

# 🔗 Pipes in Linux (|)  
A pipe takes the output from one command and passes it as input to another.

- Syntax:  
  `command1 | command2`  
- Example:  
  `ls | sort` lists files and sorts them alphabetically.

# PRACTICE PROGRAMS  

# DAY 4 :  
### PC HARDWARE :  
# Motherboard (Main Circuit Board)  

The **motherboard** is the main printed circuit board inside a computer. It connects and enables communication between essential components like the CPU, RAM, storage devices, GPU, and power supply.

## Key Components on the Motherboard

| Component               | Description                                            |
|------------------------|--------------------------------------------------------|
| **CPU Socket**          | Slot for installing the central processing unit (CPU). |
| **RAM Slots (DIMM Slots)** | Slots for installing RAM modules.                      |
| **24-pin and 8-pin Power Connectors** | Supply electrical power to the motherboard and CPU.   |
| **SATA Ports**          | Connect hard drives and SSDs.                           |
| **IDE Connector**       | Connects older hard drives or optical drives.          |
| **AGP / PCI / PCIe Slots** | Expansion slots for GPUs, sound cards, network cards, etc. |
| **BIOS/UEFI Chip**      | Stores firmware for booting and hardware configuration. |
| **USB Ports**           | Connect external devices such as keyboards and flash drives. |
| **Audio, VGA, HDMI, and Modem Ports** | Provide audio, video, and modem connections.     |
| **Fan Connectors**      | Power and control for cooling fans.                     |
| **Heat Sink Area**      | Place to attach heat sinks or CPU coolers.              |
| **CMOS Battery**        | Maintains BIOS settings like date and time when the PC is off. |

## Various Components of the CPU  

| Component             | Description                                              |
|-----------------------|----------------------------------------------------------|
| **Expansion Slots**   | Slots to add components like graphics or sound cards.    |
| **Fan**               | Helps cool the system by pushing out hot air.            |
| **Optical Drive**     | Reads and writes CDs/DVDs, mainly for media or software installation. |
| **Connectors**        | Ports on the computer case for USB, audio, HDMI, etc.    |
| **Power Supply Unit (PSU)** | Converts AC power to DC for computer components.      |
| **Hard Disk Drive (HDD)**   | Main storage device for OS, files, and programs.       |

## Difference Between Hard Disk, RAM, and Cache Memory

| Feature              | Hard Disk (HDD/SSD)            | RAM (Random Access Memory)    | Cache Memory               |
|----------------------|-------------------------------|------------------------------|----------------------------|
| **Type**             | Non-volatile storage           | Volatile memory              | Volatile memory            |
| **Speed**            | Slowest                       | Faster than HDD              | Fastest memory             |
| **Purpose**          | Stores OS, programs, and files permanently | Temporarily holds data and programs currently in use | Stores frequently accessed data close to the CPU |
| **Location**         | Separate storage device        | Installed on motherboard     | Built into or near the CPU |
| **Data loss on power off** | No                        | Yes                          | Yes                        |
| **Typical Size**     | Hundreds of GB to multiple TB  | 4GB to 64GB                  | Few MBs to tens of MBs      |
| **Cost per GB**      | Lowest                        | Moderate                     | Highest                    |

### FILE COMPRESSION :

## What is File Compression?  
File compression reduces the size of files to save disk space or make file transfer faster by encoding data more efficiently and removing redundancy. Compressed files can be decompressed later to restore the original data.

## gzip, gunzip, and gzip -k Commands

| Command           | Description                                | Effect on Original File      | Output File           |
|-------------------|--------------------------------------------|-----------------------------|-----------------------|
| `gzip file`       | Compresses a file using gzip compression    | Original file is deleted     | `file.gz`             |
| `gunzip file.gz`  | Decompresses a gzip file                      | `.gz` file is deleted       | Decompressed `file`   |
| `gzip -k file`    | Compresses a file but keeps the original     | Original file remains        | `file.gz` and original file |

### WILDCARDS :  

## Wildcards in File Matching

| Wildcard | Meaning                        | Example       | Matches                                |
|----------|--------------------------------|---------------|---------------------------------------|
| `*`      | Matches zero or more characters | `*.txt`       | All files ending with `.txt`           |
| `?`      | Matches exactly one character   | `file?.txt`   | Matches `file1.txt`, `fileA.txt` but not `file10.txt` |
| `[a-z]`  | Matches one character in the specified range | `file[0-9].txt` | Matches `file0.txt` to `file9.txt`     |

## ESCAPING CHARACTERS :

## Common Escape Characters

| Escape Sequence | Meaning                | Example Usage           | Output / Explanation           |
|-----------------|------------------------|-------------------------|-------------------------------|
| `\n`            | Newline (line break)   | `Hello\nWorld`           | Prints:  
Hello  
World (on two lines)       |
| `\t`            | Horizontal tab         | `Hello\tWorld`           | Prints: `Hello    World` (with tab space)   |
| `\\`            | Backslash character    | `C:\\Users\\Name`        | Prints: `C:\Users\Name`              |
| `\"`            | Double quote character | `He said, \"Hello\"`     | Prints: He said, "Hello"             |
| `\'`            | Single quote character | `It\'s sunny`            | Prints: It's sunny                   |


