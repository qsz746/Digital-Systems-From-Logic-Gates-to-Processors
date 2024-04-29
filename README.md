# Digital-Systems-From-Logic-Gates-to-Processors
This is a course from coursera


 I was using a Windows laptop and running Ubuntu 22.04 as a virtual machine on VirtualBox. Within this Ubuntu 22.04 virtual machine, I was also running DigitalSystemsVM on VirtualBox.
 I encountered this error 
 <br>
 <br>
 "vt-x is not avail able (verr_vmx_no_vmx) ubuntu"   
 <br>
 <br>
 when I was trying to run the DigitalSystemsVM

so I fixed this issue by runing these commands on windows command prompt

```
cd "C:\Program Files\Oracle\VirtualBox"

VBoxManage modifyvm Ubuntu2 --nested-hw-virt on
```
