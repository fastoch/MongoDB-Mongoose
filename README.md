# MongoDB & Mongoose

https://www.freecodecamp.org/learn/back-end-development-and-apis/#mongodb-and-mongoose

# Intro

**MongoDB** is a database application that stores JSON documents (or records) than you can use in your application.  
Unlike SQL, another type of database, MongoDB is a non-relational or "NoSQL" database.  
This means MongoDB stores all associated data within one record, instead of storing it across many preset tables.  

**Mongoose** is a popular npm package for interacting with MongoDB.  
With Mongoose, you can use plain JavaScript objects instead of JSON, which makes it easier to work with MongoDB.  
Also, it allows you to create **blueprints** for your documents called **schemas**, so you don't accidentally save the wrong type of data.  

---

# Install & set up Mongoose

In this challenge, you'll set up a MongoDB Atlas database and import the required packages to connect to it.  
MongoDB Atlas is a MongoDB Database-as-a-Service platform, which means that they configure and host the database for you.  
Then, your only responsibility will be to populate your database with what matters: data.

- Create a MongoDB Atlas Account: https://account.mongodb.com/account/register
- Once you create and verify your account, answer the onboarding questions and click the green Finish button.
- On the "Deploy your cluster" page, select M0 (Free), leave everything else as default, and click "Create Deployment"
- Create a database user (admin) 

