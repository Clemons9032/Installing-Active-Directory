<p align="center">
  <img width="866" height="650" alt="Active Directory Setup" src="https://github.com/user-attachments/assets/5e7866cc-ac94-4540-8b0b-ef76f1e59b3a" />
</p>

<h1>Active Directory - High Level Installation and Deployment</h1>


> [!Important]
> If starting from this walk-through, it's best to go back to the previous setup to get the full breakdown of configurations for the virtual machines used in this demonstration.

[![My Skills](https://skillicons.dev/icons?i=azure,windows)](https://skillicons.dev)

- Microsoft Azure
- Remote Desktop Protocol
- Windows Server 2022

<h2>Operating Systems Used</h2>

<img width="700" height="417" alt="Operating Systems" src="https://github.com/user-attachments/assets/2a5f0107-6016-4887-be55-035130165652" />

<h2>List of Prerequisites</h2>

- Microsoft Azure Account
- 2 Virtual Machines

<h2>High-Level Deployment and Installation Steps</h2>

> [!Important]
> Each step will include written instructions and corresponding screenshots. Expand the "See screenshots" section to view the images and progress through the portfolio.

<h3>1. Log into Domain Controller VM</h3>

<p>So the first thing i'm going to do is to log into DC-1 VM. To do that, get the public IP address of DC-1 and open up remote desktop. The easiest way to do that is to press the start key and type in remote desktop. Once it's open, type in the the ip address and log in using the credentials of dc-1.</p>


<details><summary>See screenshots</summary>
<img src="images/AD_Config_Step1.png"
</details>


<details><summary>See screenshots</summary>
<img src="images/AD_Config_Step2.png"
</details>


<details><summary>See screenshots</summary>
<img src="images/AD_Config_Step3.png"
</details>


<p>Upon logging into the DC-1 VM, the windows server manager screen will appear and from here, this is where i'm going to start the installation of Active Directory.</p>

<h4>2. Installation of Active Directory</h4>

<p>So in order to start the AD installation, I'm going to click on add roles and features. Once I click on that button, a list of services will appear and from that list, I'm going to click on Active Directory Domain Services.</p>

<details><summary>See screenshots</summary>
<img src="images/AD_Config_Step7.png"
</details>

<p>So in order to start the AD installation, I'm going to click on add roles and features.</p>

<details><summary>See screenshots</summary>
<img src="images/AD_Config_Step8.png"
</details>

<p>On the before you begin screen, just click to continue to the select installation type screen</p>

<details><summary>See screenshots</summary>
<img src="images/AD_Config_Step9.png"
</details>

<p>On this screen, make sure the role-based install is selected and click continue</p>

<details><summary>See screenshots</summary>
<img src="images/AD_Config_Step10.png"
</details>
<p>You'll get to the select destination server screen and on this screen, choose the select server from server pool option and choose your server. In my case, I only have one server to choose from.</p>

<details><summary>See screenshots</summary>
<img src="images/AD_Config_Step11.png"
</details>
<p>On the server role screen,I'm going to choose the active directory domain services for the server role.</p>

<details><summary>See screenshots</summary>
<img src="images/AD_Config_Step12.png"
</details>

<details><summary>See screenshots</summary>
<img src="images/AD_Config_Step13.png"
</details>

<details><summary>See screenshots</summary>
<img src="images/AD_Config_Step14.png"
</details>

<details><summary>See screenshots</summary>
<img src="images/AD_Config_Step15.png"
</details>

<details><summary>See screenshots</summary>
<img src="images/AD_Config_Step16.png"
</details>

