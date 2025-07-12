# Creating a User in Active directory

Connect to the EC2 Instance via RDP
Go to your AWS Console → EC2 → Connect → RDP client.
Download the .rdp file and use your domain credentials to log in.

Open "Active Directory Users and Computers"
Start → Search → Type "active" → Open

<img width="778" height="782" alt="image" src="https://github.com/user-attachments/assets/bb29e78a-2c9b-4ace-a3ac-0d4cd2cfdc47" />

Navigate to Your Desired OU
Browse the tree under your domain to locate the OU where you want to create the user.

Create a New User
Right-click the OU → New → User

<img width="1118" height="714" alt="image" src="https://github.com/user-attachments/assets/e2c466a4-0b9f-4736-b321-75cc523661b2" />


Fill in:
First name
Last name
User logon name (e.g., last.first@blank.com)
Click Next

Set Password and Options
Assign a strong password
Choose options like:
User must change password at next login
Password never expires (optional)
Click Next → Finish

Confirm the User is Created

<img width="753" height="528" alt="image" src="https://github.com/user-attachments/assets/381c5c44-598c-4d57-a38c-21bbe76c5f6a" />


The user should now appear in the list within the selected OU.

Below is a link to a Loom video of me preforming these actions 

https://www.loom.com/share/cd08e8607f68450d9ca53162011f26e8



﻿## Creating a Group in Active directory
