# task-3-mongodb


# LibraryDB Project

This readme is  outlines the specific MongoDB shell commands used to achieve project outcomes. 
Include collections for **Books**, **Authors**, and **Patrons**.


- **Database Name**: `LibraryDB`
  - **My Collections**: `Books`, `Authors`, `Patrons`


## MongoDB Shell Commands

### 1. **Create Database**
-mongosh
To create and switch to the `LibraryDB` database:
- use LibraryDB;

**Creating collections**
- db.books.insertMany([]}
-  db.Authors.insertMany([]}
-   db.Patrons.insertMany([]}

  **CRUD Operations**

  -Find :db.Books.find().pretty();
  -db.books.find({ title: "To Kill a Mockingbird" });
  - db.books.find({ author_id: 5 });
  - db.books.find({ available: true });

  -Update:
- i used updateOne
- used updateMany


-Delete:
- i used deleteOne


**Advanced Queries with Operators**


![1](https://github.com/user-attachments/assets/2c491458-0881-44ac-9c2d-7e46a6cc79d1)

![2](https://github.com/user-attachments/assets/c24d56a1-fdd3-4a3f-9c6b-90a482539075)
![3](https://github.com/user-attachments/assets/476af730-238b-48f7-a8e5-2cb64216935a)
![4](https://github.com/user-attachments/assets/c83b0cc9-39f9-44b0-87b5-d8f082131900)
