# Fundamentals-of-MongoDB-and-Github
As a activity I tried to create a basic DataBase using mongoDB compass
# MongoDB Basic Database Project

## Description

This project demonstrates the basics of MongoDB, including creating a database, collections, and performing CRUD (Create, Read, Update, Delete) operations using MongoDB shell commands.

## Technologies Used

* MongoDB
* MongoDB Shell (mongosh)

## Features

* Create a database:<img width="1915" height="1017" alt="Screenshot 2026-03-26 093048" src="https://github.com/user-attachments/assets/4e959b17-98f0-4df2-9fd8-64a18ce2013a" />

* Create collections:<img width="1915" height="1017" alt="Screenshot 2026-03-26 093048" src="https://github.com/user-attachments/assets/e3f09e6e-1a48-405e-b1de-f463e9fe61b6" />

* Insert documents:<img width="1915" height="1017" alt="Screenshot 2026-03-26 093048" src="https://github.com/user-attachments/assets/9cac8b61-eac8-4376-a4f3-82353dd0750a" />

* Read/query documents: <img width="1915" height="1017" alt="Screenshot 2026-03-26 093048" src="https://github.com/user-attachments/assets/959ef9c4-4dd4-462f-b852-245f26c5bec3" />
<img width="1919" height="1021" alt="Screenshot 2026-03-26 093155" src="https://github.com/user-attachments/assets/86155b5f-72f4-41d5-9540-5a4a2067e719" />


* Update documents: <img width="1919" height="1014" alt="Screenshot 2026-03-26 093735" src="https://github.com/user-attachments/assets/a6e1409f-8417-44ae-b444-8e7a1c22372a" />

* Delete documents:<img width="1919" height="1014" alt="Screenshot 2026-03-26 093735" src="https://github.com/user-attachments/assets/9bbe4bd9-e024-4909-a4d6-394316cc5759" />

*Drop collection: <img width="1911" height="1022" alt="Screenshot 2026-03-26 094020" src="https://github.com/user-attachments/assets/9c37a7a0-9a4f-4f36-b573-d1bf2ad7be05" />
<img width="1916" height="1009" alt="Screenshot 2026-03-26 094058" src="https://github.com/user-attachments/assets/22395982-b618-4770-9106-596f0ae62667" />



## How to Run

1. Install MongoDB on your system

2. Open MongoDB shell using:
   mongosh

3. Run the commands provided in the project files

##  Sample Commands

### Create Database

use myDatabase

### Create Collection

db.createCollection("users")

### Insert Data

db.users.insertOne({
name: "Alice",
age: 22,
city: "Bangalore"
})

### Read Data

db.users.find()

### Update Data

db.users.updateOne(
{ name: "Alice" },
{ $set: { age: 23 } }
)

### Delete Data

db.users.deleteOne({ name: "Alice" })

## Project Structure

* use admin
use Puni's_Grocery_Store
db.createCollection("Items_info")
db.Items_info.insertOne({Item_no:1,Item:"Sugar",Price_per_unit:45,Stock:522})
db.Items_info.insertMany([{Item_no:2,Item:"Salt",Price_per_unit:13,Stock:1000},{Item_no:3,Item:"Rice",Price_per_unit:700,Stock:500}])
db.Items_info.find()                                  ^
db.Items_info.updateOne({Item_no:2},{$set:{Price_per_unit:699}})
db.Items_info.deleteOne({Item_no:1})
db.Items_info.deleteMany({Item_no:2},{Item_no:3})
show collections
db.Items_info.drop()
show collections


##  Author

Your Name
Punith D

