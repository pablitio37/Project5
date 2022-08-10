# Project5
# implementing client server architecture

## IMPLEMENT A CLIENT SERVER ARCHITECTURE USING MYSQL DATABASE MANAGEMENT SYSTEM (DBMS).

To demonstrate a basic client-server using MySQL Relational Database Management System (RDBMS), follow the below instructions

Create and configure two Linux-based virtual servers (EC2 instances in AWS).
On mysql server Linux Server install MySQL Server software.

On mysql server Linux Server install MySQL Server software.

![text1](https://user-images.githubusercontent.com/108102087/184008951-0ec3dd81-18db-4b85-92ea-02fee2c46494.PNG)

On mysql client Linux Server install MySQL Client software.

![text2](https://user-images.githubusercontent.com/108102087/184009322-42c82cab-f891-4d38-af05-6a3d0c0dddfb.PNG)

By default, both of your EC2 virtual servers are located in the same local virtual network, so they can communicate to each other using local IP addresses. Use mysql server's local IP address to connect from mysql client. MySQL server uses TCP port 3306 by default, so you will have to open it by creating a new entry in ‘Inbound rules’ in ‘mysql server’ Security Groups. For extra security, do not allow all IP addresses to reach your ‘mysql server’ – allow access only to the specific local IP address of your ‘mysql client’.

User name and Database created

![TEXT3](https://user-images.githubusercontent.com/108102087/184027871-8f481c5e-fdb9-4043-be5f-88ec4ea8a322.PNG)

You might need to configure MySQL server to allow connections from remote hosts.


From mysql client Linux Server connect remotely to mysql server Database Engine without using SSH. You must use the mysql utility to perform this action.

![text4](https://user-images.githubusercontent.com/108102087/184030873-99685e15-5c9b-4cd4-8a28-871d97096f2b.PNG)

Check that you have successfully connected to a remote MySQL server and can perform SQL queries:

![text5](https://user-images.githubusercontent.com/108102087/184032032-a22fbb6d-935e-4d2e-a571-d7f76fa94762.PNG)
