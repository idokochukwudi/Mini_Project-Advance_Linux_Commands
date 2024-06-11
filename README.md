# Mini_Project-Advance_Linux_Commands

## Here are the applications of what I have learned from this topic:

## USER MANAGEMENT

### Creating a User

![](./img/3.adduser.png)

To confirm user existence. `getent passwd [username]`
![](./img/4.toknowexistinguser.png)

## Granting Administrative Privileges

![](./img/5.confirmsudouser.png)

TASK:
1. Log out and log back in as the newly created user
2. Navigate to the `/home/ziva` directory to explore what has been created `TIP:` Use the `cd` command.
## Solution:
1) To Logout
![](./img/6.tologout.png)

2) To login as the new User
![](./img/7.switcheduser.png)

## Modifying user accounts

### To change password
![](./img/8.tochangepassword.png)

## Creating a Group

- To create developers Group:
![](./img/9.addgroup.png)

## Adding user to the group
![](./img/10.addusertogroup.png)

## Verifying Group Memberships
![](./img/11.confirmusergroup.png)

## Deleting a User
![](./img/12.deleteuser.png)

## Ensuring Proper Group Permissions

### File permission commands
To manage file permissions and ownership, Linux provides several commands:

- `chmod` Command:
Example: To create empty file and check the file permission - The output after execution shows that the file is not executable.

![](./img/1.createemptyfileandcheckfilepermission.png)

- to make the file executable file using the `chmod` command - look at the screenshot below

![](./img/2.nowexecutable.png)

- `chown` Command: Allows me to change the ownership of files, directories, or symbolic links to a specified username or group.
Example:

![](./img/13.changeownershipdoc.png)

- Grant read and write permissions to the `developers` group for the directory:

![](./img/14.changegrouppermission.png)

## The above practice demonstrates my practical experience with using Linux commands.