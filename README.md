<img width="613" height="186" alt="image" src="https://github.com/user-attachments/assets/434eaaf3-c2f4-4cc9-af4d-023437fa12e6" />
<h1>Microsoft Azure</h1>
This tutorial outlines how to create a virtual machine with Microsoft Azure.<br />
<h2>Video Demonstration</h2>
-  [YouTube: How To Setup Azure Virtual Machine]([[https://www.youtube.com](https://www.youtube.com/watch?v=OCiN37sjXuw&t=138s)]
<h2>Environments and Technologies Used</h2>
- Microsoft Azure (Virtual Machines/Compute)
<h2>Operating Systems Used </h2>
- Windows 10</b> (21H2)
<h2>List of Prerequisites</h2>
- Make a Microsoft Azure Account
 -Please have remote desktop connection open for last step
<h2>Creating A Virtual Machine Within Microsoft Azure</h2>
<img width="1556" height="867" alt="image" src="https://github.com/user-attachments/assets/a47ba7df-f2c9-46e6-99d5-2af1d5a38a61" />
Once signed into your Microsoft Azure account, click on the top 3 lines, then click on virtual machines. Now, click Create and click Use Azure virtual machine. 
<h2>Setting Up Our Virtual Machine </h2>
<img width="1154" height="764" alt="image" src="https://github.com/user-attachments/assets/dd6ebd69-1dae-47d6-ad62-1cffecebe345" />
Once you have clicked on Create Virtual Machine. Set your subscription to the account you used for your Azure Account. Then you want to make a resource group and name it anything you want. In this case, I named mine MyVMGroup. 
<h2>Setting up Instance Details </h2>
<img width="1168" height="974" alt="image" src="https://github.com/user-attachments/assets/d4c5f944-5587-4412-ba10-8936aca152c5" />
You then want to name your virtual machine. In this case, I have named mine Demo-VM. For the Region, you would choose the one that's closest to you. In this case, I chose West Europe. Leave all other settings in Instance details alone aside from Image. Here, you want to press the drop-down arrow and look for the option Windows 10 Enterprise LTSC 2021- X64 Gen 2. If you need to, you can click on Run with Azure Spot Discount. 
<h2>Setting Up User Name and Password</h2>
<img width="1120" height="1100" alt="image" src="https://github.com/user-attachments/assets/21401401-996d-4d5a-9431-69dfb3fdd782" />
After you do the following steps above. Click on size and find the one named Standard_D2s_v3 - 2 vcpus, 8 GiB memory. For user name and password, you can use whatever you like, but please make a note of them so you don't forget them. For my case, I used the user name jandoe. Please do not forget to press I confirm I have an eligible Windows 10/11 license with multi-tenant hosting rights. You can then press Review + Create, as you do not need to mess with any other settings. 
<h2>Creation of Our Virtual Machine </h2>
<img width="1255" height="1821" alt="image" src="https://github.com/user-attachments/assets/3a49f0a4-7c6c-49b5-b8a5-d3c07cbea41d" />
Once everything has been run and validated, you will get a screen that looks like this. You then want to press Create and wait for the VM to deploy so that it can be used. 
<img width="1928" height="402" alt="image" src="https://github.com/user-attachments/assets/23080362-a647-435b-b708-c915137735e3" />
<h2>Bouns-Testing My Virtual Machine </h2>
<img width="1308" height="577" alt="image" src="https://github.com/user-attachments/assets/f27356d2-77a4-4e58-a945-2d98c3452ac5" />
Go to search, then look for the virtual we created. Then click on Primary NIC public IP and copy the Public IP address. 
<img width="1111" height="951" alt="image" src="https://github.com/user-attachments/assets/8591ecd9-e1e3-43b8-b3c9-3cfe6e1a05ef" />
Then, press in the Windows search bar, Remote Desktop Connection, and paste the Public IP address you copied.
<img width="569" height="280" alt="image" src="https://github.com/user-attachments/assets/c10142ab-45f9-44dd-a45d-652ff0f569ea" />
When you press connect, you want to use the username and password you created for the VM earlier.
<img width="558" height="606" alt="image" src="https://github.com/user-attachments/assets/ad24b7b7-4a94-4737-b945-6d7e9f57a52b" />
You want to click on yes after you get to this screen, after putting login info for the VM.
<img width="1588" height="1061" alt="image" src="https://github.com/user-attachments/assets/40d12f0a-330a-4d7c-99c1-fcdd649a4d77" />
After you click no on everything, press next, and there you go, you have your very own VM. 
