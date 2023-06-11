# Sparks Foundation - Basic Banking System

## Index
- [Description](#Description)
- First Time Installation
- How To Run
- Screenshot

## Description
- This a Internship project by Sparks Foundation.
- This project is built on HTML/CSS, Bootstrap, PHP and MySQL.
- Details of Customers are maintained as `Name`, `Email`, `Amount` are fields.
- Transaction is done through PDO, If some Error occured while Transaction changes made to table is Rollback(Reverted).  

## First Time Installation
- Clone the Repository.
- Make sure you have installed XAMP on your computer.
- Copy this folder(Sparks-Foundation) to XAMP installation Directory and then inside htdocs folder.

```
For Example
C:\xampp\htdocs\
```
- Open Xamp Control Panel. Click on Start button near Apache and MySQL.
- Open browser type the following into search bar.
```
http://localhost/BasicBank_System/index.php
```
- If everything works fine you would see this on your browser.
```
Conection was established Succesfully.
DATABASE Created Successfully.

```
- This means that you have created a database name bank, a table name customers also added 10 entries to table and finally creating a table name Transaction.

## How To Run
- After following steps above(First Time Installation).
- Make Sure XAMP is active with Apache and MySQL Server Enabled.
- Open Browser Enter the following URL:
```
http://localhost/BasicBank_System/
```
OR
```
http://localhost/BasicBank_System/index.php
```
- You will land to Homepage of HomePage.
- Click On `View all Customer` from Navigation OR `Get Started` button for viewing detail of all Customers.
- Now We are on Money Transfering Page and Transfer money
- Make sure the Amount you enter is not grator then current balance of the Person Selected, else it will pop Message.
- If the Transaction is successful Message will displayed and Changes made by above Transaction will be updated to customer table. 

## Screenshots
<img width="960" alt="BasicBankingsystem" src="https://github.com/Aishwariya130405/BasicBank_System/assets/121952995/16810040-9bc1-411f-bad3-0e7a440a25f2">

