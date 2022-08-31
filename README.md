<h1>Creating a Virtual Switch</h1>


<h2>Description</h2>
In this lab, I learned to create a virtual switch. A virtual switch is a software application that allows one VM (virtual machine) to communicate with another.
<br />



<h2>Environments Used </h2>

- <b>Windows Server 2016 Standard</b> 

<h2>Utilities and Language </h2>

- <b>Hyper-V Manager</b>

<h2>Program walk-through:</h2>

<p align="center">
From the desktop select Hyper-V Manager: <br/>
<img src="https://i.postimg.cc/x8vRMPdX/Screen-Shot-2022-08-30-at-8-45-31-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
<br />
In the right pane under actions click "Virtual Switch Manager":  <br/>
<img src="https://i.postimg.cc/KvZTzbt7/Screen-Shot-2022-08-30-at-8-46-57-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
<br />
Select Internal and then click Create Virtual Switch (Internal type virtual switch allows communication between virtual machines on the same Hyper-V server and between the virtual machines and the management and the management operating system) : <br/>
<img src="https://i.postimg.cc/52jyD2M0/Screen-Shot-2022-08-30-at-8-48-45-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br/>

 
  
  
<br />
Change the name of the switch and then verify that internal network button is selected then click apply then ok:  <br/>
<img src="https://i.postimg.cc/tT6qdBVt/Screen-Shot-2022-08-30-at-8-52-36-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
<br />
Navigate to the start button and then cick on Windows Powershell:  <br/>
<img src="https://i.postimg.cc/9QtLxnSX/Screen-Shot-2022-08-30-at-8-56-59-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
<br />
In Windows Powershell type in the "Get-VMSwitch" command to observe the VM Switch:  <br/>
<img src="https://i.postimg.cc/63kMyJgK/Screen-Shot-2022-08-30-at-8-59-28-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
   
  
<br />
You can now observe the VM Switch we added:  <br/>
<img src="https://i.postimg.cc/PxkFfv7y/Screen-Shot-2022-08-30-at-9-02-35-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
  
  
  
