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
After you do the following steps above. Click on size and find the one named Standard_D2s_v3 - 2 vcpus, 8 GiB memory. For user name and password, you can use whatever you like, but please make a note of them so you don't forget them. For my case, I used the user name jandoe. Please do not forget to press I confirm I have an eligible Windows 10/11 license with multi-tenant hosting rights. You can then press Review + Create as you do not need to mess any other settings. 
</p>
<br />
