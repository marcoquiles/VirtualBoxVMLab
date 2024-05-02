# Using Oracle VirtualBox to Deploy a Virtual Machine

<h2>Description</h2>
This lab demonstrates the process of setting up a virtual machine using Oracle's VirtualBox and Ubuntu 24.04 LTS. 
<br/>


<h2>Utilities Used</h2>

- <b>Oracle VirtualBox 7.0</b> 

<h2>Environments Used </h2>

- <b>Windows 11</b> (23H2)
- <b>Ubuntu Desktop 24.04 LTS</b>

<h2>Lab walk-through:</h2>

<p align="center">
<b>Downloading Ubuntu .iso</b></br>
Download Ubuntu Desktop from the official wesbite's download page: <br/>
<img src="https://imgur.com/amSVfQ2.png" height="80%" width="80%"/>
<br />
<br />
<b>Downloading and Installing VirtualBox 7.0</b></br>
At the time of writing, Oracle has issued a notice regarding an issue with VirtualBox 7.0.16. Scroll down to find a section labeled "VirtualBox older builds", where you can download the actively maintained 7.0 version.<br/>
<img src="https://i.imgur.com/DGyvMmG.png" height="80%" width="80%"/>
<br />
<br />
Choose 7.0 from the list.<br/>
<img src="https://i.imgur.com/i0uWIRd.png" height="80%" width="80%"/>
<br />
<br />
Follow the installation wizard.<br/>
<img src="https://i.imgur.com/AbkEWeU.png" height="80%" width="80%"/>
<br />
<br />
<b>Creating a Virtual Machine in VirtualBox</b></br>
Select "New" from the buttons on the right.<br/>
<img src="https://i.imgur.com/9jFs55T.png" height="80%" width="80%"/>
<br />
<br />
Enter a name for your virtual machine, browse your file system and select your ISO.<br/>
<img src="https://i.imgur.com/10M5WLv.png" height="80%" width="80%"/>
<br />
<br />
<br/>
Enter a username and password for your initial user.<img src="https://i.imgur.com/1M3ARjf.png" height="80%" width="80%"/>
<br />
<br />
Specify the resources you want your virtual machine to be created with.<br/>
<img src="https://i.imgur.com/AzPKdEo.png" height="80%" width="80%"/>
<br />
<br />
Specify the size of your virtual machine's virtual disk.<br/>
<img src="https://i.imgur.com/IiJN0b6.png" height="80%" width="80%"/>
<br />
<br />
Review your settings, and select Finish to create and start your virtual machine.<br/>
<img src="https://i.imgur.com/5N25334.png" height="80%" width="80%"/>
<br />
<br />
After hitting Finish, you should see Ubuntu initializing within your virtual machine window.<br/>
<img src="https://i.imgur.com/FERRlTA.png" height="80%" width="80%"/>
<br />
<br />
<b>Installing Ubuntu</b></br>
Once Ubuntu is done loading, you'll encounter the Ubuntu installation wizard. Follow it, making your choices accordingly.<br/>
<img src="https://i.imgur.com/1Sz2q3B.png" height="80%" width="80%"/>
<br />
<br />
You'll want to make sure you select "Install Ubuntu" to fully set up your virtual machine.<br/>
<img src="https://i.imgur.com/XwgJVpg.png" height="80%" width="80%"/>
<br />
<br />
Select "Erase disk and install Ubuntu". From your virtual machine's point of view, it will be referring to the virtual disk you created earlier. Your host disk will not be affected here.<br/>
<img src="https://i.imgur.com/0aHRT2C.png" height="80%" width="80%"/>
<br />
<br />
Create your user account.<br/>
<img src="https://i.imgur.com/MpVCJD2.png" height="80%" width="80%"/>
<br />
<br />
Wait for the installation to complete.<br/>
<img src="https://i.imgur.com/F6ShnAG.png" height="80%" width="80%"/>
<br />
<br />
When the installation finishes, you should arrive at your new virtual machine's desktop!<br/>
<img src="https://i.imgur.com/Pmpcqui.png" height="80%" width="80%"/>
<br />
<br />
</p>
