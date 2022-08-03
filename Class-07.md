# **Class 07 Reading Notes**

## **OS Upgrade and Remote Access**

### **_Why is this topic important?_**

## **OS Upgrade**

Some reasons developers put out software updates to fix problems discovered within the software.

Changing the version of the installed OS to a more current one. Windows in-place upgrades are messier than clean installs more bugs but also more convenient= faster.

Clean install wipes everthing offf the drive and performs a fresh, first time OS install

## Remote Access

To work from home

Virtual Desktop Infastructure

    - Hosting Desktop environments on a single server
    - Extremely convenient for the end user
    - Can be costly
    - Attaching local physical devices can be a hassle
    - Example Citrix

- Access company-hosted resources

- Access Cloud resources

- System Administration

### Commercial remote destop products

- Teamviewer, Splashtop, GoToMyPc

-Native Protocols

    -SSH,RDP

What is required to use RDP from outside Network?

    -A Virtual Private Network (VPN) encrytps over the internet allowing secure remote access to a host in a private network

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

-Why should we learn about powershell

 -Automate or execute the advanced operation via the terminal in windows

 -Generally used by sys administrators and engineers

 -Attackers use PowerShell to navigate through enivroments, knowing how attakers use the tools to help defend against attacks

 -Looks good on resume

## Things I want to know more about

- How to use a vpn
- How to use port forwarding for when im not at the house.
- ie gaming or work
