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



# Creating a Group in Active directory

Connect to the EC2 Instance
Open AWS Console → EC2 → Connect → Download .rdp file
Log in with domain admin credentials

Open AD Users and Computers
Start → Search → Type "active" → Open

<img width="778" height="782" alt="image" src="https://github.com/user-attachments/assets/bb29e78a-2c9b-4ace-a3ac-0d4cd2cfdc47" />

Navigate to the Organizational Unit (OU)
Expand your domain → Right-click desired OU (e.g., "Users")

Create the Group
Right-click the OU → New → Group

<img width="1063" height="641" alt="image" src="https://github.com/user-attachments/assets/0cc7b34c-a4b5-4eb9-a794-dcbb49ba1f1f" />

Enter:
Group name: e.g., IT-Support
Group scope: Global (default) or Universal
Group type: Security (default)
Click OK
Verify the Group

Group will now appear in the selected OU

<img width="756" height="536" alt="image" src="https://github.com/user-attachments/assets/8b30c895-8e32-4360-8ccf-268ede4c9a8a" />

You can double-click the group to edit properties and add members

Below is a link to a Loom video of me preforming these actions

https://www.loom.com/share/10d7f7e7739d4d7d805faaa5aa03f79f?sid=04ce8892-f30b-41c6-9b56-2a95eeefddf0


