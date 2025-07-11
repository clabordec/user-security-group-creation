<p align="center">
<img src="https://github.com/user-attachments/assets/d6aea427-8413-4b5b-aa70-b70e1964bad5" width = "550" alt="Microsoft Active Directory Logo"/>
</p>


<h1>Creating Users and Security Groups</h1>
This project outlines the creation of both user accounts and security groups within Active Directory<br />


<h2>Environments and Technologies Used</h2>

- Active Directory Domain Services (Active Directory Users and Computers)


<h2>Operating Systems Used </h2>

- Windows Server 2022


<h2>High-Level Deployment and Configuration Steps</h2>

- Create a user named `John Doe`
- Create a security group named `Clerks`
- Assign `John Doe` to the `Clerks` security group


<br>


<h1>Actions and Observations</h1>

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

### Click Finish
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

### Specify the name of the group, ensure that the group type is Security
<p>
<img src="https://github.com/user-attachments/assets/5a012fd7-772e-4d39-9223-40ae229c8eba" width="550" alt="Disk Sanitization Steps"/>
</p>

### Verify that the following group has been created
<p>
<img src="https://github.com/user-attachments/assets/1c97b9bb-b911-4b4f-ad08-ab8c158e1541" width="550" alt="Disk Sanitization Steps"/>
</p>

<br />

## Assiging the user to the group
### Right click on the Clerks security group, then click Properties
<p>
<img src="https://github.com/user-attachments/assets/02e3bbad-dee0-41e4-9a9d-5335567e4b98" width="550" alt="Disk Sanitization Steps"/>
</p>

### Go to the Members tab, then click Add
<p>
<img src="https://github.com/user-attachments/assets/7f5c9c74-b8e5-4b8b-8cd2-a204eb8f513a" width="550" alt="Disk Sanitization Steps"/>
</p>

### Enter the object name, in this case the user name, then click Check Names, the users full name along with their email address will appear in the object names input box, then click OK
<p>
<img src="https://github.com/user-attachments/assets/2c21d4b6-d7f6-4756-85b5-e86bb9419e04" width="550" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://github.com/user-attachments/assets/20271d99-172d-44aa-8073-24b8334801a8" width="550" alt="Disk Sanitization Steps"/>
</p>

### Click Apply
<p>
<img src="https://github.com/user-attachments/assets/df78d16b-ecba-4056-b74b-2139ecb35081" width="550" alt="Disk Sanitization Steps"/>
</p>

### Click OK
<p>
<img src="https://github.com/user-attachments/assets/1449ef56-0dc8-49e8-8b4a-f4d431d6e68f" width="550" alt="Disk Sanitization Steps"/>
</p>

<br />

## Verify the changes
### Right click on John Doe, then click Properties
<p>
<img src="https://github.com/user-attachments/assets/de9d1306-01b4-4a40-94e9-67a141f02368" width="550" alt="Disk Sanitization Steps"/>
</p>

### Go to the Members Of tab, and verify that the Clerks security group is in the tab
<p>
<img src="https://github.com/user-attachments/assets/d58eeaa2-4617-44aa-88e4-f438e13b0f5f" width="550" alt="Disk Sanitization Steps"/>
</p>

---

<br />


# End of Project
