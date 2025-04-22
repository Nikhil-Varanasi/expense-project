MySQL Database Setup Guide

Developer has chosen the database MySQL. Hence, we are trying to install it up and configure it.

Overview
This document provides step-by-step instructions for installing and configuring MySQL Server 8.0.x for the Expense Tracker application. MySQL serves as the persistent data storage layer in our 3-tier architecture.

Installation

1. Install MySQL Server

dnf install mysql-server -y


2. Start and Enable MySQL Service

systemctl enable mysqld
systemctl start mysqld


Configuration

3. Secure MySQL Installation
Set the root password (use `ExpenseApp@1` or your preferred secure password):

mysql_secure_installation --set-root-pass ExpenseApp@1


> Security Note: Choose a strong password and store it securely. For production environments, consider using a password manager.

Database Verification

4. Connect to MySQL Server
For local connections:

mysql -u root -pExpenseApp@1


For remote connections (replace placeholders):

mysql -h <host-address> -u root -pExpenseApp@1

5. Basic Database Operations

List all databases:
sql

Once you got mysql prompt, you can use below command to check schemas/databases exist.

SHOW databases;



Switch to our application database:
sql

USE database_name;


List tables in current database:
sql

SHOW TABLES;


View table contents:
sql

SELECT * FROM <table_name>;