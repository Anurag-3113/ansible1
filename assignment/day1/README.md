Assignment 1
 * First Step: Install Ansible manually and then configure a node machine for it and verify using ansible Ping.
  * Automating the Automation: Right a script to for the first point.
 * Add two host into hosts file.
 * check SSH login without password on both machine from remote machine.
 * Check ping on  both host
 * Check free memory through adhoc command on both sereves
 * Ansible Inventory: Use inventory, run ansible commands on various inventory groups.(Try this on minimum virtual machines.
   (You can use any of these Docker/Vagrant)

Problem statement 1: Using Adhoc command
```
Host a static website on minimum three hosts using inventory, content of static website is "Index page of Ansible assignment"
Document root /opt/html
````
 * You will need to install below software on all hosts
    * nginx
