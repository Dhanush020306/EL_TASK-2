# EL_TASK-2
# OS SECURITY FUNDAMENTALS
For this task, I am going to use kali linux, which i already have in my virtual box.
# Objectives
- To install Virtual Box and Kali Linux
- To setup environment
- To View and Manage File Permissions
- To Configure Firewall (UFW)
- Identify and disable unnecessary services
# Tools Used
- oracle virtualbox
- kali linux
# Steps Performed
**1. Installing virtual box and kali linux iso file**
  - We can install both of them from the internet, using google search engine.
   
**2. Setting Up Kali Linux in Virtual Box**
  - Click New --> Name the Machine --> Add iso file --> Finish --> Open Kali Linux.
   
**3. User Access and File permissions**
  - Using ls -l command to see file permissions
  - Using chmod command to modify permissions
  - Using chown command to change file ownership

**4. OS Hardening**
  - Listing Running Services using > systemctl list-units --type=service --state=running
  - Disable Services which are deemed unnecessary using > sudo systemctl disable
