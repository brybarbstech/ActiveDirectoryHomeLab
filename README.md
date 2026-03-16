<h1>Active Directory install and setup</h1>

<h2>Description</h2>
Project consists of a installing and setting up Active Directory in Window Server 2022.
<br />

<h2>Environments Used </h2>

- <b>Virtualbox</b>
- <b>Window Server 2022</b>

<h2>Program walk-through:</h2>

<p align="center">
Install Active Directiory: <br/>
<img src="https://gyazo.com/a177c109186de6e767e4c60f5b455c82.png" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />
Promote to domain controller:  <br/>
<img src="https://gyazo.com/f5341ef6e083e49a06c2af59ff74bd1e.png" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />
Install into PowerShell: <br/>
<img src="https://gyazo.com/bc4409451eb143f6c560100cf5b00d6f.png" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />
Open PowerShell for install:  <br/>
<img src="https://gyazo.com/b24b1f80cc01b3aa8bd7f322e0fa4718.png" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />
Install complete:  <br/>
<img src="https://gyazo.com/c82fc16ced5c972696df61f5904d71ea.png" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />
<h1>Account creation and users</h1>


<p align="center">
Open Active Directory Users and Computers: <br/>
<img src="https://gyazo.com/cc8ad053301be0043f1090ff5815da95.png" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />
I'm going to hit the drop down for bryantech.com,right click users,go to new then users:  <br/>
<img src="https://gyazo.com/ff06e5de3d9ca10981d67e8274f4692e.png" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />
Using the name Jalen as an example of creating a user. I will be making more users as well: <br/>
<img src="https://gyazo.com/29ef98b8dcff7ff3c1f7e8931532a9ed.png" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />
Users Jalen and Esa have been created in Active Directory:  <br/>
<img src="https://gyazo.com/0bf433adfa11314f59e846a6d2834791.png" height="80%" width="80%" alt="Active Directory"/>
  <h1>Joining client to domain</h1>
  

<p align="center">
Open network settings on domain controller and configure the dns: <br/>
<img src="https://gyazo.com/268a363caf30b3cd9914f8ce81f5e731.png" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />
Switch over to the Windows 11 client and change the dns server on that as well:  <br/>
<img src="https://gyazo.com/884ec8a7b32f694d4db2176c2c567700.png" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />
In the Windows 11 client, I'm going to ping the domain to make sure everything works: <br/>
<img src="https://gyazo.com/b75edf8ddc52500a9d997ffd5b85d79e.png" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />
Connect to the domain:  <br/>
<img src="https://gyazo.com/2c77175c64f6662b42a7f54855447e3d.png" height="80%" width="80%" alt="Active Directory"/>
<img src="https://gyazo.com/995b77641554f8f1caadd21c021ed193.png" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />
Checking Active Directory on the domain to make sure the client is connected:  <br/>
<img src="https://gyazo.com/a567cbb81532900a1e70b92019f11e90.png" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />
  
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
