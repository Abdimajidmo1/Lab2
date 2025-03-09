# Lab2
Code for INET3101 Lab 2 Memory structures
ab 2 Memory and Structures

OVERVIEW
This C program uses a in memory database to store and manage part records. The database uses malloc and deallocation (free) to hold the records, this gives it flexible memory management without using arrays. You can add, delete, and view records with the data stored in memory throughout the program.


FEATURES
Add Record: Adds a new part with things like part number, name, size, and cost
Delete Record: Removes the last added part
View All Records: shows all stored parts
View Number of Records: Shows the total number of parts in the database
View Database Size: shows the memory used by the database
Exit: Frees memory and exits the program

HOW TO RUN
1.Clone the repository:
    git clone (link of respository)
    cd lab2

2.Compile the code:
    cl lab2
3.Run the program:
    ./lab2
    
MENU OPTIONS
1 Print all records
2 Print number of records
3 Print size of database
4 Add a new record
5 Delete a record
6 Exit the program

EXTRA CREDIT
Skipped realloc() and instead managed the memory resizing manually (used malloc and just copy the data over yourself).

AUTHORS
Abdirizak Abdullahi
Abdimajid Mohamed
