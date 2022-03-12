# Gaming-Lounge-Database-Application

### Introduction

This project aims to implement a gaming lounge database management system, by first defining and explaining the principal entities used in this system, then going over the different queries that will be implemented, since for any system to be useful, interaction and modification of the data is essential. After defining and preparing the different parts of this system, the implementation of this system will first be made on MySQL Workbench, to define different entities and implement the queries. We will then take this project a step further by designing a graphical user interface, using C# in visual studio, to design a simple application to use and manage this database system.
In our case, to design the Gaming Lounge information storage problem, we will be having 5 main parts being:
• Customer
• Employee
• Device
• Game
• Food

However, many other entities are needed to organize different parts together, for example, bills given to each customer after playing a game or buying food, and suppliers supplying the lounge with food.


### ER Diagram

Below is an ER diagram presenting all the entities used:

![alt text](https://github.com/Hadiosj/Gaming-Lounge-Database-Application/blob/563d0e6bdd9344b3e7979b8fc88c329bbb769816/ER%20Diagram.jpg)
 
### Implementing the queries

An application was implemented in order to easily interact with and use this database system. The application was implemented using C# language in Microsoft Visual Studio, and this graphical interface was then connected to the database in MySQL workbench using ‘mysql.data.mysqlclient’, so all insert and display queries could be executed directly from the application, by opening the connection to the MySQL server and transfer data.

#### Examples of some of the queries:
1) Hire new employee, fire old employee, update the salary of a specific employee

![alt text](https://github.com/Hadiosj/Gaming-Lounge-Database-Application/blob/563d0e6bdd9344b3e7979b8fc88c329bbb769816/code%201.jpg)


![alt text](https://github.com/Hadiosj/Gaming-Lounge-Database-Application/blob/563d0e6bdd9344b3e7979b8fc88c329bbb769816/img%201.jpg)


<br />
<br />
2) Adding or deleting customers

![alt text](https://github.com/Hadiosj/Gaming-Lounge-Database-Application/blob/563d0e6bdd9344b3e7979b8fc88c329bbb769816/code%202.jpg)


![alt text](https://github.com/Hadiosj/Gaming-Lounge-Database-Application/blob/563d0e6bdd9344b3e7979b8fc88c329bbb769816/img%202.jpg)


<br />
<br />
3) Adding or deleting a game

![alt text](https://github.com/Hadiosj/Gaming-Lounge-Database-Application/blob/563d0e6bdd9344b3e7979b8fc88c329bbb769816/code%203.jpg)


![alt text](https://github.com/Hadiosj/Gaming-Lounge-Database-Application/blob/563d0e6bdd9344b3e7979b8fc88c329bbb769816/img%203.jpg)


<br />
<br />
4) Display food with expiry date in less than 30 days

![alt text](https://github.com/Hadiosj/Gaming-Lounge-Database-Application/blob/563d0e6bdd9344b3e7979b8fc88c329bbb769816/code%204.jpg)


![alt text](https://github.com/Hadiosj/Gaming-Lounge-Database-Application/blob/563d0e6bdd9344b3e7979b8fc88c329bbb769816/img%204.jpg)
