# **Class 07 Reading Notes**

## **OS Upgrade and Remote Access**

### **_Why is this topic important?_**

- You dont want to miss out on important updates. If you dont upgrade your system it is suceptiable to hackers. Remote access is an amazing capibility to be able to work not in the office but away from the office.

## **OS Upgrade**

    Some reasons developers put out software updates to fix problems discovered within the software.

    Changing the version of the installed OS to a more current one. Windows in-place upgrades are messier than clean installs more bugs but also more convenient= faster.

    Clean install wipes everthing offf the drive and performs a fresh, first time OS install

## **Remote Access**

### Virtual Desktop Infastructure

    1. Hosting Desktop environments on a single server
    2. Extremely convenient for the end user
    3. Can be costly
    4. Attaching local physical devices can be a hassle
    5. Example Citrix

- Access company-hosted resources

- Access Cloud resources

- System Administration

### Commercial remote destop products

    Teamviewer

    Splashtop

    GoToMyPc

### Native Protocols

- SSH
- RDP

- VPN

What is required to use RDP from outside Network?

- A Virtual Private Network (VPN) encrytps over the internet allowing secure remote access to a host in a private network

- Port Forwarding
  - Forwards all port traddic to the LAN PC.
    - Not ideal for most business environments, but can be good in home networks.

- What is the most useful sysadmin?
  - Desktop or Shell
- Powershell can use Windows Remoting
  - Often referred to as WinRM
  - This is encypted and supports SSL as well
  - Utilizes port 5985 and for SSL port 5986

## Powershell

Why should we learn about powershell?

- Automate or execute the advanced operation via the terminal in windows

- Generally used by sys administrators and engineers

- Attackers use PowerShell to navigate through enivroments, knowing how attakers use the tools to help defend against attacks

- Looks good on resume

## Things I want to know more about

- How to use a vpn
- How to use port forwarding for when im not at the house.
- ie gaming or work
