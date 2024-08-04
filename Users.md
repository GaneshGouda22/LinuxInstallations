## **Users** 
### Types of Users in Ubuntu:
System user(he contains executables)
User (normal user)

###### You can create a user using:
`sudo adduser <user_name>`this commmand allows you to set password for your user.
###### You can add user to specific group using:
`sudo useradd -s \bin\bash -g <id_of_group> <user_name>`ensure you have a group before you using this command.  
###### You can swich One user to annother using:
`su <user_name>`you asked to enter password. enter the password that linked to user.
##### You can delete a user using:
`sudo deluser <user_name>`