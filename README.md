# osticket


<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Setup</h1>
This tutorial outlines the post installation setup of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>List of Prerequisites</h2>

- osTicket Installed


<h2> Steps</h2>

<p>


![IMG_0622](https://github.com/user-attachments/assets/bc3ae228-7e8f-4763-a816-06415c29cccb)

</p>
<p>
First we want to get logged in to osTicket admin page
</p>
<br />

<p>

![IMG_0623](https://github.com/user-attachments/assets/601b6124-81f4-4bd4-a6fb-149714f4c6bf)

</p>
<p>
Then we want to navigate to the Agent tab and select Roles. Once there add new role and name it Supreme Admin and give it full access to all permissions
</p>
<br />

<p

![IMG_0627](https://github.com/user-attachments/assets/5086003b-7151-49db-8029-2bb9c93688d9)


</p>
<p>
Next we are going to add a new department and name it SysAdmin. After that we will create a team named Online Banking 
</p>
<br />

![IMG_0629](https://github.com/user-attachments/assets/d32c305d-1b2e-4674-9588-919895c6c01c)

![IMG_0630](https://github.com/user-attachments/assets/8ef3942c-0040-47c7-aa5d-23179c3e809d)

![IMG_0631](https://github.com/user-attachments/assets/4b3a1a2e-69e8-4366-9167-50bfde7d4fd9)


</p>
<p>
Going to Agent tab we are going to create two agents and assign them to a department and team
</p>
<br />

![IMG_0634](https://github.com/user-attachments/assets/b1e343c4-7980-4d8d-b929-de029deaafc2)

![IMG_0635](https://github.com/user-attachments/assets/f6a5d8b7-78b5-4c21-91cb-a84f3c053ddc)

![IMG_0636](https://github.com/user-attachments/assets/606a9d5d-30cf-4422-9474-c75ebb162bc5)

![IMG_0637](https://github.com/user-attachments/assets/f7955bbb-a283-4396-8b5d-465c74ca3d86)

Repeat for second user giving the same or different department or team

![IMG_0638](https://github.com/user-attachments/assets/29774b02-37f2-46e4-b879-1a6439d8f751)


</p>
<p>
Now we are going to configure SLA's. So go over to the manage tab select SLA, then Add New SLA Plan
</p>
<br />

![IMG_0646](https://github.com/user-attachments/assets/3882168d-f785-4ce8-a8eb-6629d85c33c3)

Created three diffent SLA with the following settings
![IMG_0647](https://github.com/user-attachments/assets/1d1b463b-323a-442a-9004-3cb8ace9041c)

![IMG_0648](https://github.com/user-attachments/assets/f8c101fe-c6ed-486e-898c-97c79a97ab42)
![IMG_0649](https://github.com/user-attachments/assets/f7a7e6bd-3575-49c3-819f-62e20b57df90)

</p>
<p>
Under the manage tab now select Help Topics. We are going to create a few help topics to make it easier for users when creating a ticket. These are the ones I created.
</p>
<br />

![IMG_0651](https://github.com/user-attachments/assets/e7d3fbe5-d53f-422a-8218-8290ac6ef216)

![IMG_0652](https://github.com/user-attachments/assets/2551bb54-2678-4f56-be8c-184385f61dcf)

![IMG_0653](https://github.com/user-attachments/assets/43c10c0a-e0a6-4407-919b-8f4d84f21e3b)

![IMG_0654](https://github.com/user-attachments/assets/3fcdfb0e-ac91-4461-b6c0-e3883396534d)

</p>
<p>
Finally we are going to switch over to the agent panel and create a user so a ticket can be created
</p>
<br />

![IMG_0639](https://github.com/user-attachments/assets/c8f43e2f-c10c-4e31-a6c4-3e191c667dec)

Add user and create.
![IMG_0641](https://github.com/user-attachments/assets/1bc8f58d-697f-4163-b09f-8e59f29c0e02)
![IMG_0642](https://github.com/user-attachments/assets/16c1659c-7718-48ab-a806-01c1b8d8e1f7)





</p>
<p>

</p>
<br />
