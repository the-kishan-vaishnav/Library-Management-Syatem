
# Library Management System (Python CLI Based)

## Project Description

*The Library Management System is a command-line based application that helps manage library operations like adding books, registering members, issuing and returning books, and tracking all transactions.
It stores data in JSON files, so everything persists even after the program stops running. This makes it lightweight, fast, and perfect for small libraries or beginners learning backend logic with Python.*

*It follows the traditional way libraries operate — structured records, strict issuing rules, and clean tracking of inventory.*

## Features

* Add new books with title, author, and number of copies

* Register new library members with auto-generated unique IDs

* Issue books only to registered members

* Return books and update inventory safely

* Prevent issuing when no copies are available

* Display all books in clean tabular format

* View all registered members

* Track complete transaction history (issue & return)

* Data persistence using JSON files

* Error handling for missing or corrupt data files

## Tech Stack

1. Programming Language: Python 3

2. Data Storage: JSON files

       books.json

       members.json

       transactions.json

3. Core Libraries Used:

        datetime

        random

        json

4. Architecture Type: CLI (Command Line Interface) Based System

## How to Run the Project

*Clone the Repository*
   
        git clone https://github.com/the-kishan-vaishnav/library-management-system.git

*Navigate to Project Folder*
   
        cd library-management-system

*Ensure Python Is Installed*

    Check Python version:

        python --version

*Create Required JSON Files*:
*Make sure these files exist in the project folder:*

       books.json
   
       members.json

       transactions.json

*Run the Application*
   
        python library_management.py


## Project Structure

library-management-system/

│

├── library_management.py

├── books.json

├── members.json

├── transactions.json

└── README.md
