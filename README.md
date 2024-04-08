# Active-Directory
#Active Directory Project within Virtual Box

##Introduction

In this Project, I used Orcale Virtual Box to create and build a mini virtual Active Directory. The goal of this project is to create a virtual (AD) and replicate a real AD environment for basic testing, training, and scalability.



![Active Directory Project SC](https://github.com/Dabortiz/Active-Directory/assets/164569697/3d498012-cae9-43e9-b2c2-08bc98f9c8aa)

I first started by downloading Orcale Virtual Box and then creating a VM housing our active directory. This VM will be created with 2 network adapters, one network adapter will be used to connect to the public internet while the other used to connect to the Virtual Box's private newtwork. I installed Server 2019 to the VM and assinged an IP address for the internal network. After this process, I installed the Active Directory and created the Domain. I configured the Nat and routing so that the cilents from the private newtork and reach the internet via the Domain controller. Next I set up a DHCP on the VM so whenever I create the windows 10 machine and automatic IP address will be assigned. After this step, I ran a powershell script on the VM to create the 1000+ users. Finally I will creating an additional VM and installing windows 10 and this VM will be connected with the private internal network. 
