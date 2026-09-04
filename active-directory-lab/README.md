# Active Directory Home Lab

## Project Overview

Built a virtualized Windows enterprise environment using Windows Server 2022 and Windows 11 Pro to gain hands-on experience with Active Directory administration and common Help Desk tasks.

The lab simulated user and computer administration, account management, Group Policy, file permissions, domain joining, remote access, and endpoint patch management.

## Lab Environment

| Component         | Details             |
| ----------------- | ------------------- |
| Hypervisor        | Oracle VirtualBox   |
| Server OS         | Windows Server 2022 |
| Client OS         | Windows 11 Pro      |
| Domain            | `charlie.local`     |
| Domain Controller | `FL-DC-01`          |
| Client            | `Desktop01`         |
| Patch Management  | Action1             |

## Objectives

* Deploy and configure an Active Directory Domain Controller
* Create and manage user accounts and security groups
* Join a Windows 11 workstation to the domain
* Configure and test Group Policy
* Configure shared folder and NTFS permissions
* Simulate common Help Desk account management tasks
* Perform Windows patch management using Action1

## Key Tasks Completed

### Active Directory & User Management

* Deployed Windows Server 2022 as a Domain Controller.
* Created the `charlie.local` Active Directory domain.
* Created and managed user accounts using Active Directory Users and Computers.
* Practiced disabling/enabling accounts, account expiration, logon-hour restrictions, and account lockout recovery.

### Domain & Workstation Administration

* Configured a Windows 11 Pro workstation and joined it to the `charlie.local` domain.
* Tested network connectivity and domain communication.
* Logged into the workstation using an Active Directory user account.
* Performed remote access testing between the server and client.

### Group Policy

Configured and tested Group Policy settings including:

* Maximum password age
* Minimum password length
* Account lockout threshold
* Desktop wallpaper
* Screen saver timeout
* Task Manager restrictions
* Logoff restrictions

### File & Access Management

* Created shared folders for different departments.
* Created security groups to manage access to shared resources.
* Assigned users to security groups.
* Configured and tested NTFS and network share permissions.

### Patch Management

* Connected the Windows Server environment to Action1.
* Deployed the Action1 agent.
* Identified and deployed missing Windows updates.
* Reviewed patch management, vulnerability, and installed software reports.

## Skills Demonstrated

* Active Directory Domain Services (AD DS)
* Windows Server 2022
* Windows 11
* Group Policy
* User & Account Administration
* Security Groups
* NTFS & Network Share Permissions
* DNS & Network Troubleshooting
* Domain Joining
* Remote Administration
* Patch Management
* Action1
* VirtualBox

## Results

Successfully built and tested a functional Active Directory environment consisting of a Windows Server 2022 Domain Controller and Windows 11 domain-joined workstation. The lab provided hands-on experience with administrative and troubleshooting tasks commonly performed by Help Desk and IT Support technicians.

## Technical Evidence

Screenshots and detailed documentation are included in the project documentation to demonstrate the configuration and testing performed throughout the lab.

