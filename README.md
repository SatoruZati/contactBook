# contactBook
This program creates a ContactBook class with methods to add, view, search, update, and delete contacts. The main function provides a user-friendly interface to interact with the contact book.
However, python program does not store contacts persistently if we dont use any file storage method. In such cases if we exit the program, all contacts will be lost. If we want to store contacts persistently, we use a database or file storage.

This program uses file storage to persistently store contacts. when you run the program, it will load contacts from the 'contacts.json' file, and any changes you make will be saved to the file. If the file doesn't exist, it will be created.
