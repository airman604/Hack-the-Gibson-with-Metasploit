# Welcome To BSides Vancouver 2019 *Hack the Gibson with Metasploit* Workshop!

This workshop will teach what Metasploit is and its modules. We will then proceed to scanning using Metasploit, dropping payloads and popping a Meterpreter shell, all of this using a custom made vulnerable virtual machine just for this workshop.
We will also cover Metasploit for privilege escalation and pivoting. 

## What You'll Need For This Workshop

This is a hands on workshop and you should come prepared to be able to participate. You will need:

* A laptop with VirtualBox installed
* A Virtual Machine with the latest Kali installed. This will be the 'Hacker' box. Please make sure your Kali VM works before the workshop
* Custom Vulnerable Virtual Machine that can be downloaded from [here](https://drive.google.com/open?id=15RVGMjVkAEdn6AWi2hcndvUpC-PQJPFA)
* Working knowledge in Linux
* Working knowledge in VirtualBox

## Setup Notes

* Make sure the Kali Virtual Machine is up-to-date by running the following commands:
    ```
    sudo apt-get update
    sudo apt-get full-upgrade
    ```
* For least amount of networking issues, please configure both the virtual machines to use 'NAT Network'. There are many online resources on how to configure 'NAT Network' on VirtualBox. 
  Here is one such resource- https://blog.pythian.com/test-lab-using-virtualbox-nat-networking/

## Reading Materials

* [How to import existing vm in VirtualBox](https://docs.oracle.com/cd/E26217_01/E26796/html/qs-import-vm.html)
* [Metasploit Guide By Offensive Security](https://www.offensive-security.com/metasploit-unleashed/)


### Notes
* Although the authors of this workshop have tested the lab in VirtualBox, the attendees must be prepared to troubleshoot their virtual environment incase there are issues. Help will be provided.
* There might poor or absence of Internet connectivity during the workshop. Please download the necessary applications and files before the workshop. 
