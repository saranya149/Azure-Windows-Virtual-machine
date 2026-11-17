# Azure Virtual Machine in Windows

## Overview
This project documents the steps to create, connect to, and manage a Windows Server Virtual Machine on Microsoft Azure using Remote Desktop (RDP).

## Requirements
- Active Azure subscription
- Windows laptop with Remote Desktop Connection (mstsc)
- Internet access

## Steps Covered
- Creating a Resource Group
- Provisioning a Windows Server 2025 Virtual Machine
- Selecting region, availability zone and VM size
- Allowing RDP (port 3389) in the Network Security Group
- Connecting to the VM using Remote Desktop Connection
- Running basic commands: `whoami`, `hostname`, `ipconfig`, `curl ifconfig.me`

## Tools Used
- Azure Portal
- Remote Desktop Connection (RDP)
- Windows Server 2025
- Server Manager / Command Prompt

## Real-Time Use
- Hosting IIS websites and .NET applications
- SQL Server and file servers
- Active Directory and jump servers
- Testing and training environments

## Advantages
- No hardware needed, ready in minutes
- Pay only for what you use
- Easy to scale up or down

## Disadvantages
- Costs money while running (stop the VM when not in use)
- Windows licensing makes it more expensive than Linux
- Open RDP port is a security risk (restrict to your IP in real projects)

## Screenshots
Add your lab screenshots in a `screenshots/` folder (hide the public IP and username).

## Author
Saranya T
