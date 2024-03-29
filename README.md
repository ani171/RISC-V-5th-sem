# RISC-V-5th-sem

This repository contains lab exercises completed during the 5th semester of engineering for the RISC-V course. These labs focus on practical applications of RISC-V architecture, utilizing the Ripes tool for simulation and assembly. Explore and enhance your understanding of RISC-V through hands-on exercises.

## Virtual Box Installation

https://www.virtualbox.org/wiki/Downloads
* Follow the link to access the downloads page. Download and install the Windows host version of the software.
* Launch the VirtualBox application and select "New."
* Provide a name for the virtual machine (VM) and designate the folder location for your VM files.
* Obtain the ISO file by installing the image from the specified websites.
  * For Ubuntu: http://ubuntu-releases.mirror.net.in/ubuntu/releases/jammy/ubuntu-22.04.3-desktop-amd64.iso
* Choose and download one of the two ISO files, then include it in the ISO option.
* For the type, select "Linux," and for the version, choose "Ubuntu 22.04 (64-bit)."
* Keep the rest of the settings at their default values. If you encounter any issues at this stage, please feel free to direct message either one of us for assistance.
* Click "Next," and for the base memory, set it to "2048MB" if you have less than 8GB RAM. If you have more, set it to "4096MB."
* For the processors, leave it at "1" unless you have 4 or more cores. If you have more than 4 cores, you can set it to "2."
* Click "Next," and in the "Create a virtual hard disk now" section, set it to either 50GB or 100GB. Ensure you have enough space, but note that the allocated space is dynamic and will only use up to 100GB when necessary.
* Click "Next" and then "Finish."

## RISC-V GCC Compiler

* To obtain the RISC-V GCC compiler, navigate to the following link: https://www.embecosm.com/resources/tool-chain-downloads/. Download and install the tar.gz file that corresponds to your Linux version. It's crucial to perform this installation on the Virtual Machine.
* For Ubuntu

![image](https://github.com/ani171/RISC-V-5th-sem/assets/97838595/61c31d19-2c29-43c3-a632-bfa1f3915658)

## Assembler Directives
#### .text
* The .text directive designates a read-only section that houses the actual instructions of the program.
* This section, also referred to as the code segment or text segment, is dedicated to executable instructions that remain unmodifiable during runtime.
* Any attempt to alter the contents of the .text section will result in a "Segmentation" error, leading to the immediate termination of the program. Alongside instructions, the code segment may include constants.

#### .data
 * The .data directive signifies a read-write section within the object file, reserved for storing data related to program variables.
 * The .data section is used for initialized static variables, encompassing global and static local variables.

## Data 

1. Word: In RISC-V, a word typically refers to a 32-bit value. It is the standard unit of data and address manipulation in the instruction set architecture.
2. Half Word: A half word in RISC-V consists of 16 bits or two bytes. It is often used for operations involving smaller numerical values.
3. Double Word: A double word is a larger data unit in RISC-V, comprising 64 bits or eight bytes. It is commonly used for handling larger numerical values or memory addresses.
4. Byte: The byte is the smallest addressable unit of memory in RISC-V, consisting of 8 bits. Bytes are used for storing characters and small data values.



