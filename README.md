<p align="center">
<img src="https://github.com/user-attachments/assets/d6aea427-8413-4b5b-aa70-b70e1964bad5" width = "550" alt="Microsoft Active Directory Logo"/>
</p>


<h1>Creating Users and Security Groups</h1>
This project outlines the creation of both user accounts and security groups within Active Directory<br />


<br>


<h2>Environments and Technologies Used</h2>

- Active Directory Domain Services (Active Directory Users and Computers)


<br>


<h2>Operating Systems Used </h2>

- Windows Server 2022


<br>


<h2>High-Level Deployment and Configuration Steps</h2>

- Create a user named `John Doe`
- Create a security group named `Clerks`
- Assign `John Doe` to the `Clerks` security group


<br>


<h2>Deployment and Configuration Steps</h2>

## Creating the user
### In the USA OU, go to Users >> Right-click on the Accounting OU >> Click New > Click User
<p>
<img src="https://github.com/user-attachments/assets/0f3918ee-cfd4-420c-ad87-bd590aebcd6d" width="550" alt="Disk Sanitization Steps"/>
</p>

### Enter in the following data, then click Next
<p>
<img src="https://github.com/user-attachments/assets/e75d0e4f-6ed1-4a34-bf4f-ef7c6b9ae5e7" width="550" alt="Disk Sanitization Steps"/>
</p>

### Enter a secure password
<p>
<img src="https://github.com/user-attachments/assets/3e4992e6-da92-42fc-99a1-5730a61acd09" width="550" alt="Disk Sanitization Steps"/>
</p>

### Click finish
<p>
<img src="https://github.com/user-attachments/assets/d69e9389-571a-44a9-8804-e648e2cfc35e" width="550" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://github.com/user-attachments/assets/f1eb43fe-17da-4cb0-b357-26fd63b7185e" width="550" alt="Disk Sanitization Steps"/>
</p>


<br />


## Creating the security group
### In the USA OU, go to Users >> Right-click on the Accounting OU >> Click New > Click Group
<p>
<img src="https://github.com/user-attachments/assets/0d090446-9386-413e-ab6b-c6495d9d27f3" width="550" alt="Disk Sanitization Steps"/>
</p>
![image](https://github.com/user-attachments/assets/5a012fd7-772e-4d39-9223-40ae229c8eba)

<br />

### Be sure to check the Licensing to aviod any errors
<p>
<img src="https://github.com/user-attachments/assets/bef855ee-cdf5-42d8-89b3-c9d63783953f" width="550" alt="Disk Sanitization Steps" />
</p>
<br />


### Click on the Network section and assign the `windows-vnet` to the VM
<p>
<img src="https://github.com/user-attachments/assets/46cbaada-41c5-4b4a-8ff2-56c7c03cd2a0" width="550" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://github.com/user-attachments/assets/aa0a4ed0-dc9d-42c9-9f5d-668c4d5a1d6b" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />


## Create the Client VM
<p>
<img src="https://github.com/user-attachments/assets/4464316f-abee-404d-ae8b-b2b088ea2692" width="550" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://github.com/user-attachments/assets/164d5f17-eab8-4069-a19a-0290babcd27e" width="550" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://github.com/user-attachments/assets/0d3405ee-d765-4377-b9b6-ca7e57dba340" width="550" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://github.com/user-attachments/assets/aa6d7898-799f-4492-8837-8a8368a47cd8" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Be sure to check the Licensing to avoid any errors
<p>
<img src="https://github.com/user-attachments/assets/81729691-70c9-4e22-8252-53bbb41403a4" width="550" alt="Disk Sanitization Steps" />
</p>
<br />

### Click on the Network section and assign the `windows-vnet` to the VM
<p>
<img src="https://github.com/user-attachments/assets/12f9bb63-b623-4c2f-a656-5e54882d75af" width="550" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://github.com/user-attachments/assets/c10dbb36-1000-47dd-aee9-3aaf3213cbb0" width="550" alt="Disk Sanitization Steps" />
</p>
<br />

### Set `client-1` DNS settings to match `dc-1` Private IP address
<p>
<img src="https://github.com/user-attachments/assets/b0729472-1c35-4ec5-a92c-8658ba2af405" width="550" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://github.com/user-attachments/assets/2a1f8bf2-a9f3-4fac-be5c-7ef9534cd4ce" width="550" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://github.com/user-attachments/assets/2a1f8bf2-a9f3-4fac-be5c-7ef9534cd4ce" width="550" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://github.com/user-attachments/assets/63ade75b-fedd-4798-86be-6cd3d7cf446a" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Get the private IP address from `dc-1`
<p>
<img src="https://github.com/user-attachments/assets/605cd1e8-ffcc-45a5-b817-61236d9aaecb" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Enter `dc-1` private IP address as the DNS server for `client-1`
<p>
<img src="https://github.com/user-attachments/assets/dc8b5e32-ecdb-4719-822b-dd472bf96306" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Restart `client-1` from the Azure Portal
<p>
<img src="https://github.com/user-attachments/assets/813ef37b-6794-458e-af21-759faa6c8719" width="550" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://github.com/user-attachments/assets/813ef37b-6794-458e-af21-759faa6c8719" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Log into `client-1` and run the `ipconfig /all` command to view all internet protocal configurations
<p>
<img src="https://github.com/user-attachments/assets/f5ea1c2e-a2dd-4da7-b028-5870a012b1d4" width="550" alt="Disk Sanitization Steps"/>
</p>


---

<br />


# End of Project
