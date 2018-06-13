# SQL_Create_Read_Update_Delete_homework
practise on creating, reading, updating and deleting SQL Database from cmd
SQL Homework

The Dominion Cinema are having a Marvel Movie Marathon! They have asked you to help maintain their database of movies with times and attendees.

To access the database:

First, create a database called 'marvel'

# terminal
createdb marvel
Next, run the provided SQL script to populate your database:

# terminal
psql -d marvel -f marvel.sql
Use the supplied data as the source of data to answer the questions. Copy the SQL command you have used to get the answer, and paste it below the question, along with the result they gave.

Questions

Return ALL the data in the 'movies' table.
Return ONLY the name column from the 'people' table 3.Oops! Someone at CodeClan spelled Davina's name wrong! Change it to reflect the proper spelling (change 'Davinda Sanders' to 'Davina Sanders').
Return ONLY your name from the 'people' table.
The cinema is showing 'Batman Begins', but Batman is DC, not Marvel! Delete the entry from the 'movies' table.
Create a new entry in the 'people' table with the name of one of the instructors.
Zsolt, has decided to hijack our movie evening, Remove him from the table of people.
Somehow the list of people includes two people named 'Andrew'. Change these entries to the proper names ('Jeff 4', 'Jeff 5')
The cinema has just heard that they will be holding an exclusive midnight showing of 'Guardians of the Galaxy 2'!! Create a new entry in the 'movies' table to reflect this.
The cinema would also like to make the Guardian movies a back to back feature. Update the 'Guardians of the Galaxy' show time from 18:55 to 21:30
Extension

Research how to delete multiple entries from your table in a single command.
