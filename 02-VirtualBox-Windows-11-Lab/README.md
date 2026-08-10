# VirtualBox Windows 11 Lab

## Overview

Created a Windows 11 virtual machine using Oracle VirtualBox to gain hands-on experience with virtualization, virtual hardware configuration, operating system installation, and troubleshooting.

This lab also created the Windows client machine that will later be used for Active Directory, networking, and help desk practice.

## Tasks Completed

- Installed Oracle VirtualBox on a Windows 11 host computer
- Downloaded an official Windows 11 ISO
- Created a new Windows 11 virtual machine
- Configured the VM with 4 GB of RAM
- Assigned 2 virtual processors
- Created an 80 GB virtual hard drive
- Enabled EFI, Secure Boot, and TPM 2.0
- Attached the Windows 11 ISO to the virtual machine
- Performed a manual Windows 11 Pro installation
- Completed Windows 11 initial setup
- Installed VirtualBox Guest Additions
- Improved display resizing and mouse integration
- Renamed the Windows client to `TymarsVM-Client01`
- Verified the virtual machine boots and operates successfully

## Troubleshooting

### Virtual Machine Failed to Boot From Windows ISO

**Problem:**  
After starting the virtual machine, the system displayed a message stating that no bootable device could be found.

**Cause:**  
The Windows installation ISO was attached correctly, but the "Press any key to boot from CD or DVD" prompt timed out before a key was pressed.

**Solution:**  
Reset the virtual machine and immediately pressed a key when the boot prompt appeared. The virtual machine then successfully booted from the Windows 11 ISO and started Windows Setup.

## What I Learned

- How a Type 2 hypervisor is used to run virtual machines
- How to create and configure a virtual machine
- How virtual CPUs, RAM, and storage are assigned to a VM
- How ISO files can be used as virtual installation media
- How EFI, Secure Boot, and TPM relate to Windows 11
- How virtual machines boot from attached installation media
- How to troubleshoot a failed virtual machine boot
- How VirtualBox Guest Additions improve VM usability
- How virtual machines can be used to build a larger IT home lab

## Skills Practiced

- Oracle VirtualBox
- Virtualization
- Windows 11 Pro installation
- Virtual hardware configuration
- EFI
- Secure Boot
- TPM 2.0
- ISO installation media
- Operating system deployment
- Virtual machine troubleshooting
- Guest Additions
- Windows computer naming and configuration

## Result

Successfully created and configured a functioning Windows 11 Pro virtual machine in VirtualBox. The virtual machine is now prepared to be used as a Windows client for future Active Directory, networking, and help desk labs.

## Screenshots

<img width="150" alt="8DC929CB-E227-43C9-9625-D28033A47221" src="https://github.com/user-attachments/assets/01fd4a13-fd10-48f7-a391-22d09e0a309c" />
<img width="150" alt="1B33E822-B689-41F9-8CE4-E250C0170C62" src="https://github.com/user-attachments/assets/fa51f8b8-8405-41b4-b49d-2816ff010e63" />
<img width="150" alt="IMG_3840" src="https://github.com/user-attachments/assets/5d979323-8608-48ff-b5ef-53dab6efa927" />
