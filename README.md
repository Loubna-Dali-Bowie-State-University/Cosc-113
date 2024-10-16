# Cosc-113 Programming Assignement 

Homework Lab: Using Parameterized Constructors in Java 

Problem Statement:
You are tasked with creating a Library Management System where you will define a class LibraryBook that stores information about books in a library. The class should have a parameterized constructor to initialize the attributes of the book. Use the Scanner class to get input from the user to create and manage individual LibraryBook objects, without using arrays.

Class Requirements:

Create a class called LibraryBook with the following attributes:

bookTitle (String)
authorName (String)
numberOfPages (int)
publicationYear (int)
price (double)
Implement a parameterized constructor that initializes all the above attributes.

Implement the following methods:

displayBookInfo(): This method should display all the details of the book.
isOldBook(): This method should check if the book is more than 10 years old based on the current year and return a boolean value.
isExpensive(): This method should check if the price of the book is above $100 and return a boolean value.
Use the Scanner class to take input from the user and create multiple LibraryBook objects, but do not use arrays.

After entering all the details, display the information of each book using the displayBookInfo() method. Additionally, indicate whether the book is old (more than 10 years old) and whether it is expensive (price above $100).

Instructions:
Class Definition:

Define the LibraryBook class with the attributes bookTitle, authorName, numberOfPages, publicationYear, and price.
Parameterized Constructor:

Implement the constructor to initialize the attributes.
Methods:

displayBookInfo(): Displays book details.
isOldBook(): Determines if the book is old (more than 10 years).
isExpensive(): Determines if the book costs more than $100.
User Input:

Use the Scanner class to ask the user how many books they want to input.
For each book, dynamically create an object and use the displayBookInfo() method to show the book's details.
