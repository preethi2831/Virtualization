# Virtualization
## Ex.3(A-C) Virtualization: Installation and Configuration of Oracle VirtualBox & Kali Linux, and Execution of Linux Commands

NAME: Preethika N
REG NO: 212223040130

## AIM: 
To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.

## 3.a) Installation and Configuration of Oracle VirtualBox

Aim:
To install and configure Oracle VM VirtualBox.

Pre-requisites:
Machine with Internet access

Minimum 4 GB RAM

Sufficient storage space

Steps:
1.Download Oracle VM VirtualBox:

Visit Oracle VirtualBox Official Site

Download installer for your OS (Windows/macOS/Linux).

2.Install Oracle VM VirtualBox (Example: Windows):

Launch Installer → Allow Changes → Click Next.

Choose Installation Options → Click Next.

Accept Network Interface Warning → Click Yes.

Click Install.

Finish Installation and Launch VirtualBox.

3.Configure VirtualBox:

Open VirtualBox.

Click New → Name VM → Select Type (Linux/Windows) and Version.

Allocate:

Minimum 2 GB RAM

Create Virtual Hard Disk (20 GB recommended).

Start Virtual Machine and provide ISO to install OS.

Result:
Thus, Oracle VM VirtualBox was installed successfully.

3.b) Installation and Configuration of Kali Linux
Aim:
To install and configure Kali Linux in Oracle VirtualBox.

Pre-requisites:
Oracle VM VirtualBox Installed

4 GB RAM and 20 GB Storage Minimum

Kali Linux ISO image

Steps:
1.Download Kali Linux ISO:

Visit Kali Linux Official Site

Download 64-bit ISO (Installer version).

2.Create a New Virtual Machine:

Open VirtualBox → Click New.

Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit).

3.Allocate Memory:

Minimum 2 GB RAM (recommended 4 GB).
4.Create Virtual Hard Disk:

Select VDI (VirtualBox Disk Image).

Choose Dynamically allocated.

Set Disk size to 20 GB or more.

5.Configure ISO Image:

Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali Linux ISO.
6.Start Installation:

Boot Virtual Machine → Choose Graphical Install.

Set Language, Region, Keyboard.

Configure Network → Set Hostname (e.g., kali).

Set root password.

Disk Partitioning: Use entire disk → All files in one partition.

Install System → Install GRUB Bootloader → Finish Installation.

7.Login to Kali Linux:

Use root credentials.
8.(Optional) Install Guest Additions:

Devices → Insert Guest Additions CD Image → Follow steps inside Kali.

## Snapshots:

AWS Account Creation Snapshot

Snapshot 1: Installing Oracle VirtualBox

<img width="1919" height="999" alt="image" src="https://github.com/user-attachments/assets/38e5e4e3-7813-4f85-ad95-7acaba82c56c" />

Snapshot 2: Kali Running in Virtual

<img width="1603" height="974" alt="image" src="https://github.com/user-attachments/assets/21ba5f9c-fedd-4757-8868-c930cd8c7cb3" />

## 3.c) Execution of Linux Commands in Kali
About Linux:
Open-source operating system.

Kernel manages communication between hardware and software.

Commands are case-sensitive.

Linux Commands:
1.ls Command

The ls command is used to display a list of content of a directory.

Syntax:
 ls
 
<img width="714" height="70" alt="image" src="https://github.com/user-attachments/assets/6648c70d-27df-47f8-82d5-baca4d95d5b6" />

2.pwd Command

The pwd command is used to display the location of the current working directory.

Syntax:
pwd

<img width="193" height="67" alt="image" src="https://github.com/user-attachments/assets/b608dcb1-35e1-4fb4-a526-62c2c082365c" />

3.mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax:
mkdir <directory_name>

<img width="364" height="49" alt="image" src="https://github.com/user-attachments/assets/f0885a14-4ae8-493a-8584-102078a3ef05" />

4.rmdir Command

The rmdir command is used to delete a directory.

Syntax:
rmdir <directory_name>

<img width="308" height="50" alt="image" src="https://github.com/user-attachments/assets/ca2dd6ad-20ee-4a75-8134-9885b569055c" />

5.cd Command The cd command is used to change the current directory

Syntax:
cd <directory_name>

<img width="223" height="42" alt="image" src="https://github.com/user-attachments/assets/04cf1fe5-186d-43d3-9055-8a4db7a1b8e1" />

6.cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content ofthe file, copy the content of one file to another file, and more.

Syntax:
cat [options] [file_name]

<img width="632" height="73" alt="image" src="https://github.com/user-attachments/assets/542d2010-3eba-435d-a677-63926c832848" />

<img width="866" height="71" alt="image" src="https://github.com/user-attachments/assets/83469885-4500-44a7-bdb5-ce4bd43f2d2e" />

7.cp Command

The cp command is used to copy a file or directory.

Syntax:
cp [source] [destination]

<img width="300" height="52" alt="image" src="https://github.com/user-attachments/assets/bd68616b-c23b-45c0-95e8-560f497b67b5" />
<img width="831" height="62" alt="image" src="https://github.com/user-attachments/assets/cefe4804-16a7-4b6e-9fbd-f450fdd9006d" />

8.mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax:
mv [source] [destination]

<img width="293" height="52" alt="image" src="https://github.com/user-attachments/assets/46e27d8e-b39d-4e84-9057-a22d4dca7fe9" />
<img width="339" height="64" alt="image" src="https://github.com/user-attachments/assets/7089a59e-0bb1-4eb7-9178-24dbce69ddcb" />

9.touch Command

Create empty file.

Syntax:
touch [filename]

<img width="185" height="44" alt="image" src="https://github.com/user-attachments/assets/28759951-d40b-4036-954b-98130df3fbc1" />

10.vi Command

Edit file contents using editor.

Syntax:
vi [filename]

<img width="192" height="51" alt="image" src="https://github.com/user-attachments/assets/f6dd1a2c-6ab2-4758-ad2f-1126398aa5ae" />

## RESULT:
Thus, various Linux commands were executed successfully in Kali Linux virtual machine.
