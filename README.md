
# NoSQL Databases - Summary


## Introduction

We began this section by comparing and contrasting relational/SQL databases with the NoSQL databases. The four different kinds of NoSQL databases are: 

* Document Stores
* Key-Value Stores
* Column Stores
* Graph Databases


## MongoDB

Next, we explored how to install **_MongoDB_** and get the **_MongoDB Server_** up and running. We learned some commands that we could use to interact with mongo right there in the server shell, and then focused on connecting to our MongoDB server with Python. 

You should remember the following high-level takeaways from MongoDB:

* You use the `pymongo` library and a little boilerplate code to connect to the MongoDB database. 
* In MongoDB, records are referred to as **_Documents_**. 
* We can create groups of documents called **_Collections_**. 
* Records are inserted by passing in our data as Python dictionaries. 
    * We can insert a single record with our collection object's `.insert_one()` method. 
    * We can insert many records by creating a list of dictionaries and passing the entire list to the collection object's `.insert_many()` method. 
* We can write queries by using the collection object's `.find()` method. 
* We can **_filter_** our queries by passing in the key-value pairs to filter by. 
* We can also use logic on our filters by making use of **_modifiers_**. 

## Summary

Congrats! You are now a (No)SQL wizard! It doesn't matter whether the data you want is stored in a SQL or a NoSQL database, you can access it with ease. 
