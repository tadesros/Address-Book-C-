# Address-Book
Creating an Address Book File System



Project Overview:

​This purpose of this project was to create a file based database to store and update a contact / address list.  This was a final project in my database systems class.   The project was to be completed using an object oriented design in C++.   

The final project contains two classes:  create_record and address_book.

The create_record class creates/populates a text file in the proper format for the address_book class to use.  The create_record class can also create a transaction file which contains commands to update an existing address book record.  

For more details see the header (.h) and  implementation (.cpp) files below.


address_book class:

Once a data or transaction file has been completed the address_book class can be used.   An address_book object reads in all of the address records and stores them in an array of structs.  The user has the option to display the records,  update using a transaction file or create a new master record file.

The header and implementation files of the Address_book class is listed below. 

The file main.cpp creates a menu for to utilize the create_record and address_book classes.  


