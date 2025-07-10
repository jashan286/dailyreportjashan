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

# DAY 5:
## Common PC Problems and Solutions
Help Shortcut: Press F1 to open help tool in Windows.

Today we learned about common issues encountered on personal computers and how to fix them. Each point includes both the cause and the recommended solution.

## PC Maintenance Issues
### C Drive Full or Slowing Down
The C drive stores essential system files. Avoid saving personal files here. Free space using Disk Cleanup, uninstall unused programs, or move data to D or E drive. You can also delete temporary files using %temp%.

### PC Running Slowly
Caused by too many background processes or lack of memory. Open Task Manager to disable startup apps, delete temp files, and remove unused software.

### Fragmented Hard Drive (HDD only)
Fragmentation slows down file access. Use "Defragment and Optimize Drives" in Windows to improve speed (note: not needed for SSDs).

### Too Many Temporary or Junk Files
These files build up from software usage. Use Disk Cleanup or manually delete files from %temp%, temp, and prefetch folders.

### System Takes Long to Start
Caused by unnecessary startup programs and services. Disable unwanted startup applications using Task Manager under the "Startup" tab.

## Software & Application Issues
### Software Freezes or Crashes
Can happen due to corrupted installations or insufficient RAM. Force quit using Task Manager and reinstall or update the app.

### Software Installation Fails
Common reasons include lack of admin permissions or incompatible versions. Use "Run as administrator" and ensure correct 32/64-bit installer is downloaded.

### Windows Update Not Working
Sometimes the update cache is corrupted. Run the Windows Update Troubleshooter or delete contents in C:\Windows\SoftwareDistribution folder.

## Hardware & Peripheral Issues
Printer Not Responding
Usually caused by driver problems or connection issues. Restart the printer and PC, check cable or network, and reinstall drivers if needed.

### Drive Not Detected
A new or unformatted drive won’t show in Explorer. Go to Disk Management, assign it a drive letter, and format if necessary.

### Computer Automatically Restarts or Overheats
Often caused by clogged fans or poor airflow. Clean the dust from CPU fan, vents, and use cooling pads for laptops. Also check if thermal paste needs reapplying.

## Network & Security Issues
### Internet Not Working Despite Being Connected
Likely a DNS or driver issue. Restart the router, run Windows Network Troubleshooter, or open Command Prompt and run ipconfig /flushdns.

### Antivirus Slowing Down the System
Heavy or multiple antivirus programs can reduce speed. Use only one trusted antivirus (like Windows Defender), and disable unnecessary real-time scanning features.

## Account & Graphics Issues
### Forgotten Login Password
For local accounts, use Safe Mode or reset via another admin account. For Microsoft accounts, reset using Microsoft’s online password recovery.

### Low Graphics Performance
Happens due to outdated GPU drivers or background apps using resources. Download latest drivers from NVIDIA/AMD and close all unnecessary apps during usage.

## What is Blue Screen of Death (BSOD)?
The Blue Screen of Death (BSOD) is a critical system error screen displayed by Windows when the operating system can no longer operate safely due to a severe issue. It is also called a Stop Error or bug check.

## Why Does BSOD Happen?
BSOD typically occurs due to:

Faulty device drivers (graphics, network, etc.)
Corrupted system files
Faulty or incompatible hardware (RAM, hard drive, GPU)
Overheating or power issues
Malware affecting system-level processes
Overclocking or BIOS misconfigurations
Critical kernel or memory management errors

## How to Analyze a BSOD?
Read the Error Message
The BSOD screen will display a STOP CODE like:
DRIVER_IRQL_NOT_LESS_OR_EQUAL or CRITICAL_PROCESS_DIED.

Use Reliability Monitor
Open Reliability Monitor (search in Start menu) to check system events before the crash.

View Dump File After a BSOD, Windows creates a dump file that records what happened before the crash. Analyze crash dumps stored at:
C:\Windows\Minidump\ using tools like:

BlueScreenView (NirSoft)
WinDbg (Microsoft Debugger)
WhoCrashed
Event Viewer
Use eventvwr.msc to see system logs and warnings before the BSOD occurred.

## Solutions to Fix BSOD
Step	Action
1. Update Drivers	Go to Device Manager and update all major drivers (especially GPU, chipset, and network).
2. Uninstall Recent Software	Remove any software or drivers recently installed before the BSOD started.
3. Run System File Checker	Run sfc /scannow in Command Prompt as administrator to repair corrupted system files.
4. Check RAM	Run Windows Memory Diagnostic to check for faulty memory.
5. Scan for Malware	Use Windows Defender or Malwarebytes to check for deep infections.
6. Reset Overclocking	If using overclocked settings, restore BIOS/UEFI to default values.
7. Perform a System Restore	Roll back to a working system point using System Restore.
8. Update Windows	Keep the OS up to date with the latest security and stability patches.
   
## Preventive Measures
Avoid installing untrusted drivers or registry cleaners.
Keep a restore point or full backup before major updates.
Ensure proper cooling and power supply to prevent hardware issues.

## Assignment on BIOS/UEFI Settings and POST Errors
What is BIOS/UEFI?
BIOS (Basic Input/Output System) and UEFI (Unified Extensible Firmware Interface) are low-level firmware interfaces between the computer's hardware and its operating system.
BIOS is the older system, while UEFI is the modern standard in most PCs since 2010.
These interfaces allow you to configure hardware settings, boot order, security options, and more.

## Common BIOS/UEFI Settings
Setting	Description
Boot Order	Determines which device (HDD, SSD, USB) the PC checks first when starting.
Secure Boot	Prevents unauthorized OS or bootloaders from loading (enabled in UEFI).
Virtualization	Enables support for virtual machines (VT-x, AMD-V).
XMP/DOCP Profile	Enables full-speed RAM performance (must be manually enabled in some PCs).
Fan Control	Sets custom cooling profiles based on temperature.
Date/Time	Sets the system clock — affects OS time if incorrect.
SATA Mode	Selects IDE, AHCI, or RAID for hard drive behavior.
Integrated Peripherals	Enables/disables onboard devices (e.g., audio, LAN, USB ports).
Password Setup	Sets BIOS or boot passwords for security.

## What is POST?
POST (Power-On Self Test) is a diagnostic process run by BIOS/UEFI during startup to check if essential hardware (CPU, RAM, GPU, keyboard, etc.) is working.

If POST fails, it usually halts the boot process and gives error beeps or messages.

### Common POST Errors & Beep Codes
Error / Beep	Meaning	Suggested Fix
No Display / Blank Screen	GPU or RAM issue	Reseat graphics card and RAM
Continuous Beeps	RAM failure	Check RAM sticks or try different slots
1 Long, 2 Short Beeps	GPU not detected	Reinsert GPU properly or test another
Keyboard Not Detected	Faulty or unplugged keyboard	Try another USB port or replace keyboard
CMOS Checksum Error	BIOS settings corrupt	Reset BIOS using Clear CMOS jumper
Date and Time Reset	CMOS battery drained	Replace the small coin-cell battery on motherboard
Beep codes vary by BIOS manufacturer (AMI, Phoenix, Award). Refer to your motherboard manual for exact beep meanings.

## How to Access BIOS/UEFI
Restart your PC and press the correct key during startup:
DEL or F2 (common for most desktops/laptops)
ESC, F1, or F10 for others
You may also access UEFI through Windows:
Go to Settings > Update & Security > Recovery > Advanced Startup > Restart Now > UEFI Firmware Settings

## Resetting BIOS/UEFI to Default
If you misconfigured a setting or can’t boot:

Enter BIOS/UEFI → Choose "Load Setup Defaults" or "Reset to Default"
Or remove the CMOS battery for a few minutes and reinsert it
Or use the Clear CMOS jumper on the motherboard
# DAY 6:
## System Troubleshooting Guide
### 1. Safe Mode
Safe Mode is a diagnostic startup mode that loads only essential system files and drivers. It is used to troubleshoot issues that prevent Windows from starting or running properly.

### Types of Safe Mode:

Safe Mode
Safe Mode with Networking
Safe Mode with Command Prompt
### How to Access:

Press Shift + Restart → Troubleshoot → Advanced Options → Startup Settings
Or interrupt boot process 3 times to enter recovery mode
## 2. Recovery Tools
Recovery Tools are built-in Windows utilities used to fix, restore, or reset system functionality after crashes, failed updates, or boot errors.

### Key Recovery Options:

Tool	Description
System Restore	Reverts the system to a previously created restore point
Startup Repair	Fixes boot-related problems automatically
Reset This PC	Reinstalls Windows with an option to keep or remove user data
System Image Recovery	Restores Windows using a full system image backup
Command Prompt	Allows advanced troubleshooting using terminal commands

### Access via:
Settings → Recovery → Advanced Startup
Or press F11/Shift + Restart during boot

## 3. OS Repair (Operating System Repair)
OS repair involves fixing core system files and configurations to restore normal Windows operations.

### Common Repair Methods:

#### Method	Description
sfc /scannow	Scans and repairs corrupted system files
DISM /RestoreHealth	Repairs the Windows image if SFC is not sufficient
Startup Repair	Automatically fixes boot-related files
Reset This PC	Reinstalls Windows while offering data preservation options
Commands: sfc /scannow DISM /Online /Cleanup-Image /RestoreHealth

## Virus and Malware
### Symptoms of Infection
System becomes slow or unresponsive
Frequent crashes or freezes
Unexpected pop-ups or ads appear
Antivirus software is disabled automatically
Unknown programs start running or installed
Files or folders are missing, renamed, or encrypted
High CPU, memory, or disk usage without visible cause
Browser redirects to unknown websites or search engines
## Basic Malware Removal Steps
### Boot into Safe Mode with Networking

Press Shift + Restart → Troubleshoot → Advanced Options → Startup Settings
### Run Full System Scans

Use Windows Defender or a trusted tool like Malwarebytes
### Uninstall Suspicious Applications

Go to Control Panel → Programs → Uninstall unknown software
### Disable Unwanted Startup Programs

Open Task Manager → Startup tab → Disable unknown entries
### Reset Browsers

Remove unknown extensions and reset settings in Chrome, Firefox, etc.
### Review Scheduled Tasks and Services

Use Task Scheduler and services.msc to identify unusual entries
### Perform System Restore or Reset This PC

Use a restore point or reinstall Windows to eliminate persistent threats
## Networking Cable and Connectors
### Ethernet Cable and RJ45 Connector
Ethernet cables are used to connect computers, routers, and switches for network communication.
 The RJ45 connector is a standard 8-pin connector used at both ends of the cable.
### RJ45 Color Code (TIA/EIA 568B Standard)
Wiring order from left to right (with clip facing down):

White-Orange, Orange, White-Green, Blue, White-Blue, Green, White-Brown, Brown

### Pin Number	Wire Color
1	White-Orange
2	Orange
3	White-Green
4	Blue
5	White-Blue
6	Green
7	White-Brown
8	Brown

## Crimping Basics

Crimping is the process of attaching an RJ45 connector to the end of a network cable.

### Steps:

Strip about 1 inch of outer cable jacket.
Untwist and arrange the wires in the correct color order.
Trim all wires to the same length.
Insert wires into the RJ45 connector.
Use a crimping tool to lock the connector in place.
### Cable Testing
After crimping, a cable tester is used to check:

Proper pin connections (1 to 1, 2 to 2, etc.)
Continuity across all 8 wires
No shorts, opens, or miswiring
A basic tester will light up each pin in sequence to show a successful connection.

## day 7:-
### Network:
A computer network is a group of two or more interconnected computer systems that share data and resources through communication channels.

### Host:-
A host is a network-connected device assigned with an IP address, which allows it to participate in communication over a network.

### Server:-
A server is a powerful host machine in a network that runs server software and responds to client requests, such as hosting websites, storing files, or managing emails.

### Client:-
client-server network, the client refers to the device or software that initiates requests and interacts with the user.

### Traffic:-
Network traffic is the flow of data packets over a network, including all types of communication such as browsing, file transfers, video streaming, emails, etc.

### IP address:
full form: Internet Protocol. where protocol refers to the set of rules which govern the data transmission. Properties:

Unique: Each device on a network must have a unique IP address.

Universal: IP addresses are a globally recognized standard for network communication.

## Types:

### Public IP Address: Used on the internet, these addresses are globally unique and routable.

### Private IP Address: Used within private networks (e.g., home or school networks), these addresses are not directly routable on the internet.

### Dynamic Nature: IP address can change over time, especially for devices on dynamic IP assignments. However, its fundamental properties (uniqueness and universality) remain constant.

## IPV4:
Internet Protocol version 4 An IPv4 address consists of series of four eight-bit binary numbers which are separated by decimal point. Although any numbering system can be used to represent a unique 32- bit number, most commonly you see IP address expressed in dot decimal notation.

## IPv4 Address Format:
An IPv4 address consists of 32 bit (binary digit), grouped into four section of known as octets or bytes. Each octet has 8 bits and this bits can be represented only in 0 or 1 form, and when they grouped together, they form a binary number. Since each octet has 8 bits, it can represent 256 numbers ranging from o to 255. These four octets are represented as decimal numbers, separated by periods known as dotted decimal notation. For example IPv4 address 185.107.80.231 consists of four octets.

## Binary Representation:
IPv4 is basically converted into binary form by computer although these are usually seen in decimal form for human readability. Each octet is converted into 8 bit binary number .

## IPV6:
Internet Protocol Version 6 The Internet Protocol version 6, or IPv6, is the latest version of the Internet Protocol (IP), which is the system used for identifying and locating computers on the Internet. IPv6 was developed by the Internet Engineering Task Force (IETF) to deal with the problem of IPv4 exhaustion. IPv6 is a 128-bit address having an address space of 2128, which is way bigger than IPv4. IPv6 uses a Hexa-Decimal format separated by a colon (:).

### Components in IPv6 Address Format:
There are 8 groups and each group represents 2 Bytes (16-bits). Each Hex-Digit is of 4 bits (1 nibble) Delimiter used - colon (:)

## Subnetting
subnetting is a technique used to split a network into multiple smaller networks, each with its own range of IP addresses, while still being part of the same larger network.

## Why Use Subnetting?
-Reduces network congestion

Improves security (isolates network sections)

Helps in efficient IP address allocation

Simplifies network management

## Mac address:-
A MAC address is a 48-bit unique identifier assigned to a network device by its manufacturer, used for communication within a local network (LAN).

Key Features: Permanently burned into hardware (but can be changed in software)
Expressed in hexadecimal format

Used for device-to-device communication in the same network

## DNS :-
The Domain Name System (DNS) is a hierarchical system that maps human-readable domain names to machine-readable IP addresses on the internet or within a network.

### Why DNS is Needed:
Humans remember names like youtube.com

Computers use IP addresses like 142.250.195.14

DNS acts as a translator between them

How DNS Works (Steps):
You type www.example.com in your browser.

The computer asks the DNS Resolver for the IP.

Resolver queries DNS servers in order:

### Root Server
Top-Level Domain (TLD) Server (.com, .org)

Authoritative Name Server (actual domain's IP info)

The IP address is returned to the browser.

-Browser connects to the IP and loads the website.

## default Gateway:-
A Default Gateway is the device (usually a router) that connects a local network to the internet or to another network. It acts as an access point or IP router that a device uses to send data to another network or the outside world.

### Why It’s Important:
It connects devices in your network to the internet.

Without a default gateway, devices can only communicate locally.

It helps in routing data between networks.
