<p align="center">
<img src="https://i.imgur.com/nBkHqaM.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />

<h1>How to Setup and Use a VPN | ProtonVPN</h1>


<h2>Description</h2>
In this project I create an Azure VM (Virtual Machine) where I download, install, and use a free VPN (Virtual Private Network) called ProtonVPN. <br />
<br />
VPNs (Virtual Private Networks) create encrypted tunnels for secure network connections. They are commonly used by companies to enable remote work and by individuals to access restricted content.
<br/>


<h2>Environments and Utilities Used</h2>

- <b>ProtonVPN</b>
- <b>Microsoft Azure</b>

<h2>Project Step by Step:</h2>

<p align="center">
First, I will create an Azure VM: 



![01-Setting up a VM png](https://github.com/user-attachments/assets/ad325580-ff8e-43e7-8cd6-dc17d290b0b6)

<p align="center">
Being Extra Careful to select the windows 10 disc image


![02-Setting up a VPN](https://github.com/user-attachments/assets/2bfe4d47-6a33-4e32-adde-305ac465b8df)

<br />
<br />
While that's creating I will navigate to this website https://whatismyipaddress.com to get my physical IP address and location. I will write this down in my notepad so that I can observe the changes later when we connect to our VM:  

![03-Getting original IP address](https://github.com/user-attachments/assets/1e837ef1-908d-4ac0-b4f0-a7c3e9579418)


<br />
<br />
Next, I'll connect to the VM I just created using Remote Desktop Connection:  

![04-Remote Connection to VPN Test](https://github.com/user-attachments/assets/4babe184-c960-49d7-8b1e-0b12e129415f)


<br />
<br />
Once I'm connected to my VM I will navigate to the same IP website, then observe and note the different IP and location since I set this VM up to be in Canada. (This RDP connection is like a VPN connection in the sense that there is a tunnel connecting my physical computer to the VM in a different location entirely): 
<br/>

![05-Ipaddress of VM](https://github.com/user-attachments/assets/4bf8c516-5f8a-4c71-9f3a-2a55f66425ec)

<br />
<br />
Now, I can head over to ProtonVPN and sign up for a free account:  <br/>


![06-Signing up for Proton VPN](https://github.com/user-attachments/assets/3f425cec-c5b2-4fe7-934e-376117120f9c)
<br />
<br />

After I sign in, it will take me to the homepage where I can start a VPN connection: 
<br />
<br />
![07-Using Proton Disconnected](https://github.com/user-attachments/assets/b57141e1-5372-4078-a5bb-a909cb4cc552)

<br />
<br />
I'll click on "Quick Connect" and it will choose and start a VPN connection for me:

![08-Using Proton Connected](https://github.com/user-attachments/assets/142a29f5-4495-4ceb-bd04-b74a696f03cf)


<br />
<br />
Now, if i go back to the IP address website and refresh the page, it shows me that I am in Japan instead of the US, and I have another different IP address:  


![09-New IP address](https://github.com/user-attachments/assets/ec3cf461-d02f-49cf-9bff-d495bb6594d6)


<br />
<br />
Even my home page has changed when I pull up the internet:  

![10-Japan Homepage](https://github.com/user-attachments/assets/849d9697-5ab2-4fe1-8f12-21b005595849)


<br />
<br />


<h2> The Setup and Use of Proton is now Complete!</h2>

<b> We've successfully downloaded, installed, and used a free VPN called ProtonVPN! We observed all of the different changes that happened with our IP address and location, and saw some possibilites like, accessing different content while using a VPN! </b>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
