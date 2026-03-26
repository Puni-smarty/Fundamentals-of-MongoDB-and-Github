# Fundamentals-of-MongoDB-and-Github
As a activity I tried to create a basic DataBase using mongoDB compass
# MongoDB Basic Database Project

## 📌 Description

This project demonstrates the basics of MongoDB, including creating a database, collections, and performing CRUD (Create, Read, Update, Delete) operations using MongoDB shell commands.

## 🚀 Technologies Used

* MongoDB
* MongoDB Shell (mongosh)

## 📂 Features

* Create a database
* Create collections
* Insert documents
* Read/query documents
* Update documents
* Delete documents

## ⚙️ How to Run

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

* commands.txt (or .js file with MongoDB queries)

##  Author

Your Name

