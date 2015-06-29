# Java-Swing-Address-Book
Functional Address Book GUI in Java

Base Tutorial:
http://www.wideskills.com/java-tutorial/java-swing-address-book (this uses MySQL)



# Description:
  This is a Java Application that acts like an Agenda for personal contacts. It has a graphical interface that uses Swing objects. Its main purpose is to allow user to save their contacts without ever having to open the Ms-Access Database. It is posible to connect it to any tipe of database, but I have chosen Ms-Access because it can be stored locally.
  In order to connect Java with MS-Access, I have used UCanAccess and packed the required jars into the final application.
  The GUI containts text fields that correpsond to table names (name, address, phone, email), with name being compulsory.
  
#Instructions:

The application comes with an Access Database("contacts.accdb") that HAS TO BE STORED ON DESKTOP. (The actual database could have been packed within the executable, but I want to provide direct access to its content). 

After introducing the desired data, the user can press the button SAVE to add a new contact to the database.
The user can insert a name and use the button Search by name. The user will then be presented an option list with all the matching results. After selecting the desired one, he will be able to see the contact details associated with that name.
After Searching and selecting a contact, the user can edit the details and press UPDATE or simply press DELETE to erase all data. (UPDATE and DELECTE are diasbled until a result is selected using the SEARCH button).

ENJOY!




  

