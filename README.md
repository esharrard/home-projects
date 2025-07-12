# Creating a User in Active directory

Connect to the EC2 Instance via RDP
Go to your AWS Console → EC2 → Connect → RDP client.
Download the .rdp file and use your domain credentials to log in.

Open "Active Directory Users and Computers"
Start → Search → Type "active" → Open
Navigate to Your Desired OU
Browse the tree under your domain to locate the OU where you want to create the user.

Create a New User
Right-click the OU → New → User
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

The user should now appear in the list within the selected OU.
