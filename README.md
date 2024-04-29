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
 <br>
  <br>
so I fixed this issue by runing these commands on windows command prompt
 <br>

```
-----What the commands do is to enable Nested VT-x/AMD-V for my Ubuntu vm

-----Ubuntu2 is the naming of my ubuntu vm, if your ubuntu vm has a different naming, you should replace "Ubuntu2" with your own vm name.

cd "C:\Program Files\Oracle\VirtualBox"

VBoxManage modifyvm Ubuntu2 --nested-hw-virt on
```

![image](https://github.com/qsz746/Digital-Systems-From-Logic-Gates-to-Processors/assets/55030187/f5fd6d75-00c6-47c5-8a97-1147349ea648)
