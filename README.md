# ELASTIC-SIEM 


<img src="https://img.shields.io/badge/Elastic%20Stack-005571?style=for-the-badge&logo=elastic&logoColor=white" />


<h2>Objective</h2>

In this lab I will aim to build a SIEM using ELASTIC defend that will create alerts to the users email and show how to take action based off the alert.

My aim is to show:

1. How to set-up and install a virtual machine and install Kali.
2. How to create an account with Elastic Cloud.
3. Configure your SIEM to collect logs from your Kali VM.
4. Generate alerts from your Kali VM.
5. How to take action once you recieve an alert.
   
<br />


<h2>Utilities Used</h2>

- [Virtual Box](https://www.virtualbox.org/wiki/Downloads)
- [Kali Linux](https://www.kali.org/get-kali/#kali-installer-images)
- [Elastic Cloud](https://cloud.elastic.co/login?redirectTo=%2Fhome)

<h2>Environments Used </h2>

- <b>Kali Linux VM</b>

Note: Windows users will need to enable virtualization on their PCs to run a Virtual Machine. 
  
<br />

<h2>Creating an account with Elastic Cloud:</h2>
<br />

1. Navigate to [Elastic Cloud](https://cloud.elastic.co/login?redirectTo=%2Fhome) and create a free account (14-day free trial).
2. Once you have created an account, navigate to the [portal](https://cloud.elastic.co/login?redirectTo=%2Fhome) and login.
3. Start your free trial.
4. Click on the 'Create Deployment', select 'Elasticsearch'.
5. Click continue.

<h2>Creating a Kali VM:</h2>
<br />

1. Download and install your choice of VM in this instance I will be using [Virtual Box](https://www.virtualbox.org/wiki/Downloads). Download and install the correct package for your host.
2. Download and install [Kali](https://www.kali.org/get-kali/#kali-installer-images).
3. Open Oracle VM Virtual Box Manager and click on "New".
4. You can name the VM anything you like I just called mine "Elastic SIEM". Under ISO image find and select the Kali image you downloaded prior.
5. Follow the prompts. The installation should be straightforward from here.



