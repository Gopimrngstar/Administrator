# Active Directory Home Lab

##Overview
This lab demonstrates a basic Active Directory environment built using Windows Server and Windows clients in a virtualized setup. The objective was to understand user management, group policies, and basic troubleshooting scenarios.

## Environment
- Host OS: Windows
- Virtualization: VirtualBox
- Domain Controller: Windows Server
- Client OS: Windows 10
- Network Type: Nat Network

## Lab Objectives
- Set up a Windows Server as a Domain Controller
- Create and manage AD users and groups
- Join client machines to the domain
- Apply basic Group Policy Objects
- Troubleshoot common domain-related issues

## Key Tasks Performed
- Installed and configured Active Directory Domain Services
- Created users and groups and assigned permissions
- Joined a Windows client to the domain
- Created and tested basic GPOs
- Verified DNS and domain authentication

## Common Issues & Fixes
- Client unable to join domain → Checked DNS settings and domain name resolution
- User login failure → Verified user account status and group membership

## What I Learned
- How identity and access management works in a domain environment
- Importance of DNS in Active Directory
- Structured approach to troubleshooting authentication issues
- Understanding domain controllers environment multi branch locations
