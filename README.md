# Active Directory Home Lab

## Project Overview

This project demonstrates the deployment and administration of a Windows Active Directory Domain Services (AD DS) environment using VMware Workstation.

The lab simulates a small business network with a Domain Controller and a Windows 11 client joined to the domain. Users, Organizational Units, Security Groups, and NTFS permissions were configured to demonstrate identity and access management concepts commonly used in enterprise environments.

---

## Technologies Used

- VMware Workstation
- Windows Server 2025
- Windows 11 Enterprise
- Active Directory Domain Services (AD DS)
- DNS
- Organizational Units (OUs)
- Security Groups
- NTFS Permissions
- File and Folder Sharing

---

## Lab Architecture

```
VMware Workstation

│
├── Windows Server 2025
│     • Domain Controller
│     • DNS Server
│     • Active Directory
│
└── Windows 11 Client
      • Joined to Domain
      • Authenticated with Domain Accounts
```

---

## Objectives

- Install Windows Server 2025
- Promote server to Domain Controller
- Create a new Active Directory Domain
- Join a Windows 11 client to the domain
- Create Organizational Units
- Create Domain Users
- Create Security Groups
- Assign users to Security Groups
- Configure shared folders
- Configure NTFS permissions
- Restrict folder access based on Security Groups

---

## Configuration Steps

### 1. Created Domain Controller

- Installed Active Directory Domain Services
- Promoted Windows Server to Domain Controller
- Configured DNS
- Created a new domain

Screenshot: <img width="1911" height="1439" alt="setting up Domain server with foresr" src="https://github.com/user-attachments/assets/96c2674c-1790-477b-8f22-1f96e817b767" />
<img width="2555" height="1428" alt="Me longing in from a user i created within the server" src="https://github.com/user-attachments/assets/02f952fa-627d-4f1d-bf0c-00a5fd6edcc7" />
<img width="2559" height="1439" alt="installing window server 2025" src="https://github.com/user-attachments/assets/d561baf0-b725-4e1f-9fbb-1f8e5dc0c6f3" />



![Domain Controller](screenshots/03-domain-controller.png)

---

### 2. Joined Windows 11 Client

The Windows 11 virtual machine was successfully joined to the Active Directory domain and authenticated using domain credentials.

Screenshot: <img width="2555" height="1437" alt="Creating client to connect to server and then pinging it to check connection" src="https://github.com/user-attachments/assets/93d7ee4c-f430-4e55-83ca-7c1834482f03" />


![Client Joined](screenshots/10-client-domain-joined.png)

---

### 3. Created Organizational Units

Organized objects into OUs for easier administration.

Example:

- Users
- Groups
- Computers

Screenshot: ![Uploading Me longing in from a user i created within the server.png…]()


![OU Structure](screenshots/04-active-directory-users-computers.png)

---

### 4. Created Users

Created multiple domain user accounts representing employees.

Examples:

- John Smith
- Sarah Jones
- Mike Brown

Screenshot:

![Users](screenshots/06-users.png)

---

### 5. Created Security Groups

Created department-based Security Groups.

Examples:

- HR
- IT
- Finance
- Sales

Users were assigned to their respective groups.

Screenshot:

![Security Groups](screenshots/05-security-groups.png)

---

### 6. Configured Shared Folders

Created departmental folders on the server.

Example:

```
Shared

├── HR
├── Finance
├── IT
└── Sales
```

---

### 7. Configured NTFS Permissions

Configured folder permissions using Security Groups instead of assigning permissions directly to individual users.

Steps performed:

- Disabled inheritance
- Removed unnecessary inherited permissions
- Added department Security Groups
- Granted appropriate Read/Modify access
- Verified unauthorized users could not access restricted folders

Screenshot:

![NTFS Permissions](screenshots/08-ntfs-permissions.png)

---

## Skills Demonstrated

- Active Directory Administration
- Windows Server Administration
- Domain Controller Deployment
- DNS Configuration
- Identity and Access Management (IAM)
- User and Group Management
- NTFS Permissions
- Principle of Least Privilege
- Access Control
- File Server Administration

---

## Results

Successfully deployed a functional Active Directory environment consisting of:

- 1 Windows Server 2025 Domain Controller
- 1 Windows 11 Domain Client
- Active Directory Domain Services
- Domain Users
- Security Groups
- Department File Shares
- Role-Based Access Control (RBAC) using Security Groups
- NTFS Permission Management

---

## Lessons Learned

This project strengthened my understanding of enterprise Windows administration, including Active Directory deployment, user and group management, domain authentication, and implementing secure access controls using Security Groups and NTFS permissions.
