# 🖥️ Active Directory & Windows Server Home Lab

> **Hands-on IT infrastructure lab built with VMware Workstation,
> Windows Server, Active Directory, Group Policy, DHCP, file sharing,
> and Windows 11 clients.**

## 🎯 Lab Overview

This repository documents my hands-on Windows infrastructure home lab.
The goal was to build and manage a small Windows domain environment from
the ground up and practice tasks commonly performed in **System
Administration, IAM, Infrastructure, and IT Support** roles.

### 🧰 Environment

-   🖥️ **Hypervisor:** VMware Workstation
-   🪟 **Server:** Windows Server 2025 / Windows Server 2022
-   💻 **Client:** Windows 11
-   🔐 **Directory Services:** Active Directory Domain Services (AD DS)
-   🛡️ **Security:** Group Policy, password policy, account lockout,
    USB/device restrictions
-   🌐 **Networking:** DHCP, IP configuration, connectivity testing
-   📁 **File Services:** Shared folders, NTFS/share permissions, drive
    mapping, quotas

## 🚀 Skills Demonstrated

-   Active Directory domain creation and management
-   Domain-joining Windows clients
-   User and administrative account management
-   Service account configuration
-   Organizational Units (OUs) and Group Policy
-   Password and account lockout policies
-   DHCP scope configuration and reservations
-   Network connectivity troubleshooting
-   Shared folder and permission management
-   Network drive mapping
-   Storage quotas
-   Restricting removable storage and Control Panel access
-   Client startup automation and browser configuration
-   Sysinternals tools and domain integration

## 📸 Lab Evidence

The repository contains **35 unique screenshots**. Duplicate screenshots
were removed so each lab step is represented once.

## 🖥️ Server & Active Directory Setup

### Setting up the sysinternal and connecting it to the domain +user account i created for it

![Setting up the sysinternal and connecting it to the domain +user
account i created for
it](screenshots/03-setting-up-the-sysinternal-and-connecting-it-to-the-domain-user-account-i-created-for-it.jpg)

### Creating service account(1)

![Creating service
account(1)](screenshots/10-creating-service-account.jpg)

### installing window server 2025

![installing window server
2025](screenshots/14-installing-window-server-2025.jpg)

### Admin powershell (1)

![Admin powershell (1)](screenshots/15-admin-powershell.jpg)

### Creating an admin account

![Creating an admin
account](screenshots/22-creating-an-admin-account.jpg)

### Admin domain i made so i can have client join domain(1)

![Admin domain i made so i can have client join
domain(1)](screenshots/34-admin-domain-i-made-so-i-can-have-client-join-domain.jpg)

### setting up Domain server with foresr

![setting up Domain server with
foresr](screenshots/35-setting-up-domain-server-with-foresr.jpg)

## 🌐 Networking & DHCP

### Resrvation for printer

![Resrvation for printer](screenshots/01-resrvation-for-printer.jpg)

### dhcp to domain(1)

![dhcp to domain(1)](screenshots/05-dhcp-to-domain.jpg)

### Creating client to connect to server and then pinging it to check connection

![Creating client to connect to server and then pinging it to check
connection](screenshots/06-creating-client-to-connect-to-server-and-then-pinging-it-to-check-connection.jpg)

### dhcp p2

![dhcp p2](screenshots/12-dhcp-p2.jpg)

### dhcp day lease(1)

![dhcp day lease(1)](screenshots/17-dhcp-day-lease.jpg)

### DHCP printer reservation set up

![DHCP printer reservation set
up](screenshots/26-dhcp-printer-reservation-set-up.jpg)

### Configure client to same network as domain server

![Configure client to same network as domain
server](screenshots/27-configure-client-to-same-network-as-domain-server.jpg)

### dhcp finish(1)

![dhcp finish(1)](screenshots/28-dhcp-finish.jpg)

### dhcp setup reserve

![dhcp setup reserve](screenshots/29-dhcp-setup-reserve.jpg)

## 📁 File Sharing & Permissions

### Mapping shared folder to client desktop

![Mapping shared folder to client
desktop](screenshots/02-mapping-shared-folder-to-client-desktop.jpg)

### Drive mapping for users

![Drive mapping for users](screenshots/16-drive-mapping-for-users.jpg)

### Making a network Mapp so client shared folder remains active after restarting computer

![Making a network Mapp so client shared folder remains active after
restarting
computer](screenshots/19-making-a-network-mapp-so-client-shared-folder-remains-active-after-restarting-computer.jpg)

### quota for shared folder, so space is preserve

![quota for shared folder, so space is
preserve](screenshots/20-quota-for-shared-folder-so-space-is-preserve.jpg)

### Shared folder created from server

![Shared folder created from
server](screenshots/32-shared-folder-created-from-server.jpg)

### Setting up shared permissions for file sharing

![Setting up shared permissions for file
sharing](screenshots/33-setting-up-shared-permissions-for-file-sharing.jpg)

## 🛡️ Group Policy & Security

### Putting limitation on file types for users

![Putting limitation on file types for
users](screenshots/04-putting-limitation-on-file-types-for-users.jpg)

### Created a gpo so noone else could logon as something else on the service account

![Created a gpo so noone else could logon as something else on the
service
account](screenshots/08-created-a-gpo-so-noone-else-could-logon-as-something-else-on-the-service-account.jpg)

### Desktop wallpaper group policy(1)

![Desktop wallpaper group
policy(1)](screenshots/09-desktop-wallpaper-group-policy.jpg)

### First GPO password policy(1)

![First GPO password
policy(1)](screenshots/11-first-gpo-password-policy.jpg)

### Account lockout policy to prevent brute force attack

![Account lockout policy to prevent brute force
attack](screenshots/13-account-lockout-policy-to-prevent-brute-force-attack.jpg)

### USB Storage deny GPO policy

![USB Storage deny GPO
policy](screenshots/21-usb-storage-deny-gpo-policy.jpg)

### Applying gpo to OUs

![Applying gpo to OUs](screenshots/24-applying-gpo-to-ous.jpg)

### Enabled restriction of Control panel for users

![Enabled restriction of Control panel for
users](screenshots/25-enabled-restriction-of-control-panel-for-users.jpg)

## 👤 Accounts & Domain Management

### Me longing in from a user i created within the server

![Me longing in from a user i created within the
server](screenshots/31-me-longing-in-from-a-user-i-created-within-the-server.jpg)

## 🚀 Client Configuration & Automation

### Computer starting up website automatically and at fulll screen after restart(1)

![Computer starting up website automatically and at fulll screen after
restart(1)](screenshots/07-computer-starting-up-website-automatically-and-at-fulll-screen-after-restart.jpg)

### Making prompt for window to automatically startup website after restart

![Making prompt for window to automatically startup website after
restart](screenshots/18-making-prompt-for-window-to-automatically-startup-website-after-restart.jpg)

### Setting up a website as startup to see if it works

![Setting up a website as startup to see if it
works](screenshots/30-setting-up-a-website-as-startup-to-see-if-it-works.jpg)

## 🧪 Testing & Validation

### Screenshot 2026-07-03 155533

![Screenshot 2026-07-03
155533](screenshots/23-screenshot-2026-07-03-155533.jpg)

## 🧠 What I Practiced

This lab gave me practical experience with how Windows endpoints, domain
services, users, security policies, networking, and shared resources
work together in a domain environment.

The project also helped me practice troubleshooting rather than simply
following setup instructions---for example, validating network
connectivity, applying policies to OUs, testing permissions, and
confirming that client-side changes actually took effect.

## 📈 Next Steps

-   ☁️ Extend the lab into **Microsoft Entra ID / Azure**
-   🔑 Build an **IAM-focused lab** with role-based access and lifecycle
    management
-   🐧 Add a **Linux server** and integrate it with the environment
-   📝 Document troubleshooting scenarios and resolutions
-   ⚙️ Automate repetitive administration tasks with **PowerShell**

## 👨‍💻 Project Purpose

Built as a hands-on portfolio project to demonstrate practical Windows
Server, Active Directory, networking, security, and systems
administration skills.
