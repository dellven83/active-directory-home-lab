# 🖥️ Active Directory & Windows Server Home Lab

> **Hands-on Windows infrastructure lab focused on Active Directory, Windows Server, Group Policy, DHCP, networking, file services, security, and client administration.**

## 🎯 Project Overview

This is an evolving Windows systems administration home lab built with **VMware Workstation**.

I started with a basic Active Directory environment and progressively expanded it into a more complete enterprise-style Windows environment. The lab is focused on learning by actually **building, configuring, testing, securing, and troubleshooting** the infrastructure.

## 🧰 Environment

- 🖥️ **VMware Workstation**
- 🪟 **Windows Server 2025**
- 💻 **Windows 11**
- 🔐 **Active Directory Domain Services (AD DS)**
- 🌐 **DNS & DHCP**
- 🛡️ **Group Policy**
- 📁 **SMB/File Sharing & NTFS Permissions**
- ⚙️ **PowerShell**
- 🧪 **Windows Administration & Troubleshooting**

## 🏗️ Lab Architecture

```text
                    VMware Workstation
                           │
             ┌─────────────┴─────────────┐
             │                           │
             ▼                           ▼
     Windows Server 2025           Windows 11 Client
     ───────────────────           ─────────────────
     • Domain Controller           • Domain Joined
     • Active Directory            • Domain Users
     • DNS                         • Group Policy
     • DHCP                        • Network Shares
     • Group Policy
     • File Services
             │
             ▼
      Active Directory Domain
             │
      ┌──────┼──────────┐
      ▼      ▼          ▼
    Users   Groups     Computers
      │
      ├── Accounting
      ├── HR
      ├── IT
      └── Service Accounts
```

## 🚀 Skills Practiced

- Active Directory domain administration
- Domain Controller deployment
- DNS configuration
- DHCP scope configuration
- DHCP reservations
- Windows client domain joining
- User and group management
- Administrative account management
- Service account management
- Organizational Units (OUs)
- Group Policy Objects (GPOs)
- Password policies
- Account lockout policies
- USB/removable storage restrictions
- Control Panel restrictions
- Desktop configuration
- Network drive mapping
- File sharing
- NTFS/share permissions
- Storage quotas
- Network troubleshooting
- PowerShell administration
- Client automation
- Principle of Least Privilege

## 📸 Lab Documentation

The screenshots below document the actual configuration and testing performed throughout the lab.


## 🖥️ Server & Active Directory

### Resrvation For Printer

<img src="./active-directory-home-lab-github/screenshots/01-resrvation-for-printer.jpg" alt="Resrvation For Printer" width="900">

### Putting Limitation On File Types For Users

<img src="./active-directory-home-lab-github/screenshots/04-putting-limitation-on-file-types-for-users.jpg" alt="Putting Limitation On File Types For Users" width="900">

### Creating Client To Connect To Server And Then Pinging It To Check Connection

<img src="./active-directory-home-lab-github/screenshots/06-creating-client-to-connect-to-server-and-then-pinging-it-to-check-connection.jpg" alt="Creating Client To Connect To Server And Then Pinging It To Check Connection" width="900">

### Creating Service Account

<img src="./active-directory-home-lab-github/screenshots/10-creating-service-account.jpg" alt="Creating Service Account" width="900">

### Account Lockout Policy To Prevent Brute Force Attack

<img src="./active-directory-home-lab-github/screenshots/13-account-lockout-policy-to-prevent-brute-force-attack.jpg" alt="Account Lockout Policy To Prevent Brute Force Attack" width="900">

### Installing Window Server 2025

<img src="./active-directory-home-lab-github/screenshots/14-installing-window-server-2025.jpg" alt="Installing Window Server 2025" width="900">

### Admin Powershell

<img src="./active-directory-home-lab-github/screenshots/15-admin-powershell.jpg" alt="Admin Powershell" width="900">

### Creating An Admin Account

<img src="./active-directory-home-lab-github/screenshots/22-creating-an-admin-account.jpg" alt="Creating An Admin Account" width="900">

### Screenshot 2026 07 03 155533

<img src="./active-directory-home-lab-github/screenshots/23-screenshot-2026-07-03-155533.jpg" alt="Screenshot 2026 07 03 155533" width="900">

### Me Longing In From A User I Created Within The Server

<img src="./active-directory-home-lab-github/screenshots/31-me-longing-in-from-a-user-i-created-within-the-server.jpg" alt="Me Longing In From A User I Created Within The Server" width="900">

### Shared Folder Created From Server

<img src="./active-directory-home-lab-github/screenshots/32-shared-folder-created-from-server.jpg" alt="Shared Folder Created From Server" width="900">

### Admin Domain I Made So I Can Have Client Join Domain

<img src="./active-directory-home-lab-github/screenshots/34-admin-domain-i-made-so-i-can-have-client-join-domain.jpg" alt="Admin Domain I Made So I Can Have Client Join Domain" width="900">

### Setting Up Domain Server With Foresr

<img src="./active-directory-home-lab-github/screenshots/35-setting-up-domain-server-with-foresr.jpg" alt="Setting Up Domain Server With Foresr" width="900">


## 👤 Accounts & Administration

### Setting Up The Sysinternal And Connecting It To The Domain User Account I Created For It

<img src="./active-directory-home-lab-github/screenshots/03-setting-up-the-sysinternal-and-connecting-it-to-the-domain-user-account-i-created-for-it.jpg" alt="Setting Up The Sysinternal And Connecting It To The Domain User Account I Created For It" width="900">


## 🌐 Networking & DHCP

### Dhcp To Domain

<img src="./active-directory-home-lab-github/screenshots/05-dhcp-to-domain.jpg" alt="Dhcp To Domain" width="900">

### Dhcp P2

<img src="./active-directory-home-lab-github/screenshots/12-dhcp-p2.jpg" alt="Dhcp P2" width="900">

### Dhcp Day Lease

<img src="./active-directory-home-lab-github/screenshots/17-dhcp-day-lease.jpg" alt="Dhcp Day Lease" width="900">

### Making A Network Mapp So Client Shared Folder Remains Active After Restarting Computer

<img src="./active-directory-home-lab-github/screenshots/19-making-a-network-mapp-so-client-shared-folder-remains-active-after-restarting-computer.jpg" alt="Making A Network Mapp So Client Shared Folder Remains Active After Restarting Computer" width="900">

### Dhcp Printer Reservation Set Up

<img src="./active-directory-home-lab-github/screenshots/26-dhcp-printer-reservation-set-up.jpg" alt="Dhcp Printer Reservation Set Up" width="900">

### Configure Client To Same Network As Domain Server

<img src="./active-directory-home-lab-github/screenshots/27-configure-client-to-same-network-as-domain-server.jpg" alt="Configure Client To Same Network As Domain Server" width="900">

### Dhcp Finish

<img src="./active-directory-home-lab-github/screenshots/28-dhcp-finish.jpg" alt="Dhcp Finish" width="900">

### Dhcp Setup Reserve

<img src="./active-directory-home-lab-github/screenshots/29-dhcp-setup-reserve.jpg" alt="Dhcp Setup Reserve" width="900">


## 📁 File Sharing & Permissions

### Mapping Shared Folder To Client Desktop

<img src="./active-directory-home-lab-github/screenshots/02-mapping-shared-folder-to-client-desktop.jpg" alt="Mapping Shared Folder To Client Desktop" width="900">

### Drive Mapping For Users

<img src="./active-directory-home-lab-github/screenshots/16-drive-mapping-for-users.jpg" alt="Drive Mapping For Users" width="900">

### Quota For Shared Folder So Space Is Preserve

<img src="./active-directory-home-lab-github/screenshots/20-quota-for-shared-folder-so-space-is-preserve.jpg" alt="Quota For Shared Folder So Space Is Preserve" width="900">

### Setting Up Shared Permissions For File Sharing

<img src="./active-directory-home-lab-github/screenshots/33-setting-up-shared-permissions-for-file-sharing.jpg" alt="Setting Up Shared Permissions For File Sharing" width="900">


## 🛡️ Group Policy & Security

### Created A Gpo So Noone Else Could Logon As Something Else On The Service Account

<img src="./active-directory-home-lab-github/screenshots/08-created-a-gpo-so-noone-else-could-logon-as-something-else-on-the-service-account.jpg" alt="Created A Gpo So Noone Else Could Logon As Something Else On The Service Account" width="900">

### Desktop Wallpaper Group Policy

<img src="./active-directory-home-lab-github/screenshots/09-desktop-wallpaper-group-policy.jpg" alt="Desktop Wallpaper Group Policy" width="900">

### First Gpo Password Policy

<img src="./active-directory-home-lab-github/screenshots/11-first-gpo-password-policy.jpg" alt="First Gpo Password Policy" width="900">

### Usb Storage Deny Gpo Policy

<img src="./active-directory-home-lab-github/screenshots/21-usb-storage-deny-gpo-policy.jpg" alt="Usb Storage Deny Gpo Policy" width="900">

### Applying Gpo To Ous

<img src="./active-directory-home-lab-github/screenshots/24-applying-gpo-to-ous.jpg" alt="Applying Gpo To Ous" width="900">

### Enabled Restriction Of Control Panel For Users

<img src="./active-directory-home-lab-github/screenshots/25-enabled-restriction-of-control-panel-for-users.jpg" alt="Enabled Restriction Of Control Panel For Users" width="900">


## 🚀 Client Automation

### Computer Starting Up Website Automatically And At Fulll Screen After Restart

<img src="./active-directory-home-lab-github/screenshots/07-computer-starting-up-website-automatically-and-at-fulll-screen-after-restart.jpg" alt="Computer Starting Up Website Automatically And At Fulll Screen After Restart" width="900">

### Making Prompt For Window To Automatically Startup Website After Restart

<img src="./active-directory-home-lab-github/screenshots/18-making-prompt-for-window-to-automatically-startup-website-after-restart.jpg" alt="Making Prompt For Window To Automatically Startup Website After Restart" width="900">

### Setting Up A Website As Startup To See If It Works

<img src="./active-directory-home-lab-github/screenshots/30-setting-up-a-website-as-startup-to-see-if-it-works.jpg" alt="Setting Up A Website As Startup To See If It Works" width="900">

## 🔐 Security Concepts

This lab includes practical implementation of several Windows security concepts:

- 🔑 **Password Security** — centralized password requirements through Group Policy
- 🚫 **Account Lockout** — protection against repeated failed authentication attempts
- 🔒 **Least Privilege** — limiting administrative and user access
- 👤 **Service Account Security** — separating service identities from normal users
- 💾 **Device Restrictions** — controlling removable/USB storage through policy
- 📁 **Access Control** — managing file access through groups and permissions
- 🛡️ **Centralized Configuration** — enforcing workstation settings with GPOs

## 🧠 What I Learned

The lab helped me understand how the major components of a Windows domain environment depend on each other:

```text
Networking
    ↓
DNS / DHCP
    ↓
Active Directory
    ↓
Authentication
    ↓
Organizational Units
    ↓
Group Policy
    ↓
User / Computer Configuration
    ↓
Access Control & Security
```

Rather than only following installation guides, I used the lab to experiment with configuration changes, test the results on a domain client, and troubleshoot issues when configurations did not behave as expected.

## 📈 Future Improvements

- ☁️ Microsoft Entra ID / Azure integration
- 🔑 IAM-focused identity lifecycle management
- 🐧 Linux server integration
- ⚙️ PowerShell automation
- 📝 Advanced troubleshooting scenarios
- 📊 Windows Event Log monitoring
- 🔎 File and security auditing
- 🏢 Multiple domain controllers
- 🔄 Active Directory replication
- 💾 Backup and recovery testing
- 🔐 Windows Server hardening
- 📜 Active Directory Certificate Services (AD CS)
- 🛡️ SIEM/security monitoring integration

## 👨‍💻 Project Purpose

This project is part of my hands-on development toward **System Administration, IAM, Windows Infrastructure, and Cloud/IT Engineering** roles.

The lab is continuously expanding as I learn new technologies and administration techniques.
