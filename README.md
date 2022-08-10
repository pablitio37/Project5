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
