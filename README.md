# E-Commerce Back End

## Description

[![Video Demonstration of Application](./examples/example.gif)](https://drive.google.com/file/d/19lT9RU0MzYWg8MdGB_UDtxrdZrC8P9fI/view)

This project was created as an exercise to practice creating back-end code for an e-commerce site.  It is designed to resemble the architecture of an e-commerce site.  This project uses Express.js, Sequelize, and MySQL to imitate the functionality of a store's database.  The database organizes the products into various categories and tags, and has the ability to easily get products by category, tag, or by id.  The user is also able to create new products, tags, and categories, modify existing ones, and also delete them.  

Each product is organized into one category, and may have any number of tags. 

A request to delete a category will also delete all products in that category.