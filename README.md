# workshop-asp-net-core-mvc

## :information_source: Information 

The project was developed during the C# programming course by instructor Nelio Alves. The aim of the project was to develop a sales system using the ASP .NET CORE Framework. For data storage, the MYSQL database was used. The sales system is composed of the models of: departments, salespeople and sales records. Simple grouped queries of sales records were implemented to facilitate the search for sales and their respective departments.

## ⚠️ Prerequisite
![ASPNET Badge](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)

![Mysql Badge](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)

![Bootstrap Badge](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)

![C# Badge](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)

![Html Badge](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

## Demo

![bandicam 2021-10-18 19-24-20-158](https://user-images.githubusercontent.com/44611131/137817323-8e2a4c77-f81e-4f2e-af7b-c3cde732f3e1.gif)



## :rocket: Installation

To install the project you must install mysql on your machine.

## ⚙️ Installing MySQL

Enter the following commands in the terminal.

```
sudo apt update
sudo apt install mysql-server

```
### Configuring MySQL

For new installations, you will want to run the security script that is included. This changes some of the less secure default options for things like root logins and example users. Enter the command below.

```
sudo mysql_secure_installation
```
This will take you through a series of prompts where you can make some changes to the security options of your MySQL installation. The first prompt will ask you if you want to configure the Validate Password Plugin, which can be used to test the strength of your MySQL password. Regardless of your choice, the next prompt will be to set the password for the MySQL root user. Sign in and then confirm a secure password of your choice.

From there, you can press Y and then ENTER to accept the default answers for all subsequent questions. This will remove some anonymous users and the test database, disable remote login for root, and load all of these new rules so that MySQL immediately respects the changes you made.

### Testing MySQL

To see if MYSQL is running, type the following command.

```
systemctl status mysql.service
```

If MySQL is not running, you can start it with the following command.
```
sudo systemctl start mysql

Now try to connect your root user to MySQL.
```
mysql -u root -p

### Attention when creating the database

At the visual studio terminal enter the following command to create the database. But first check your username in the MYSQL database in the file: appsettings.json

Type the following:
```
Update-Database
```
If there is any conflict with the migrations, delete them and create them again using the command
```
Add-Migration Your message

Update-Database
```

![](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)


```
git clone https://github.com/RamonBecker/workshop-asp-net-core-mvc.git
```

![](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
```
git clone https://github.com/RamonBecker/workshop-asp-net-core-mvc.git
or install github https://desktop.github.com/ 
```

## :zap: Technologies	

- ASP .NET CORE
- MYSQL
- BOOTSTRAP
- RAZOR PAGES


## :memo: Developed features

- [x] CRUD Departments
- [x] CRUD Saller
- [x] Custom Search for SalesRecords


## :technologist:	 Author

By Ramon Becker 👋🏽 Get in touch!



[<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg' alt='github' height='40'>](https://github.com/RamonBecker)  [<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg' alt='linkedin' height='40'>](https://www.linkedin.com/in/https://www.linkedin.com/in/ramon-becker-da-silva-96b81b141//)
![Gmail Badge](https://img.shields.io/badge/-ramonbecker68@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:ramonbecker68@gmail.com)
