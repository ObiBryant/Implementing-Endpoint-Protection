# Implementing Endpoint Protection

<h2>Description</h2>
In this project I will harden administrator accounts and workstations. First, I will create a fine-grained password policy that enforces stricter password setting than the Default Domain Policy. These settings will be applied to an IT-specific Global group. In the second task, I will use Group Policy to configure several security-oriented settings. The GPO created will be linked to an Organizational Unit in Active Directory where IT computer accounts reside.
<br />


<h2>Utilities Used</h2>

- <b>Server Manager</b> 

<h2>Environments Used </h2>

- <b>Windows Server 2016</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
1. Login to Domain Controller, launch Server Manager, create a group called "ITstaff": <br/>

https://github.com/ObiBryant/Implementing-Endpoint-Protection/assets/143296412/85d68630-33ff-4632-b2a9-a251f6a188d9

<br />
<br />
Password Policy Requirements: <br/>

![Endpoint Password Policy Requirements](https://github.com/ObiBryant/Implementing-Endpoint-Protection/assets/143296412/d91c019d-da99-4f1e-86c5-5f302d41b7c8)

<br />
<br />
2. Creating a fine-grained password policy for ITstaff accounts:  <br/>

https://github.com/ObiBryant/Implementing-Endpoint-Protection/assets/143296412/ca80c146-96e3-4819-b7bd-420a34149743

<br />
<br />
3. Creating an Organizational Unit: <br/>

https://github.com/ObiBryant/Implementing-Endpoint-Protection/assets/143296412/7435e659-2172-46f5-95e3-68b8bd450721

<br />
<br />
4. Configuring the Group Policy:  <br/>

https://github.com/ObiBryant/Implementing-Endpoint-Protection/assets/143296412/dbf608b2-13b4-412e-b0ad-406a41c8170e

<br />
<br />
5. Turning on Windows Defender:  <br/>

https://github.com/ObiBryant/Implementing-Endpoint-Protection/assets/143296412/1ccf39bd-e235-4b30-b9e6-7a18767ba067

<br />
<br />
6. Saving the report:  <br/>

https://github.com/ObiBryant/Implementing-Endpoint-Protection/assets/143296412/2a41fc85-f527-4b94-9731-5b8a14a3cf14

<br />
<br />
True or False: the default Domain Policy GPO defines password settings for all domain members?  <br/>

https://github.com/ObiBryant/Implementing-Endpoint-Protection/assets/143296412/dc951dd2-ca8e-4492-8b86-69a0c1ba43ec

<br />
<br />
Fine-grained password policies may be applied to what two Active Directory object types?  <br/>

https://github.com/ObiBryant/Implementing-Endpoint-Protection/assets/143296412/a3dff5ee-1d8b-4a57-b675-f1d702159ad4

<br />
<br />
Which of the following best defines a benefit of linking GPOs to OUs?  <br/>

https://github.com/ObiBryant/Implementing-Endpoint-Protection/assets/143296412/ca4eba52-3f80-49d6-9160-00bd885473ef

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
