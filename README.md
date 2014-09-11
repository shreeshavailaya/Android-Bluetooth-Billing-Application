Android-Bluetooth-Billing-Application
=====================================

Android application that communicates with the near by Bluetooth printer for printing the bills. 

The Goal of the Application in brief:

1.To build a base for small scale POS application.
2.To be able to print the receipts anywhere with portable Bluetooth Printer.
3.Introduce SMS features for tracking the ongoing sales
4.To get instant reports for daily,monthly,yearly sales there by shop owner can analyse the ongoing trends.
5.To give easy way for choosing the menu items,updating the menu items and price list.

Components of the application:
=====================================

1. Android Service: For holding the connection with bluetooth printer. Since its a background service we will not loose the 
   connection irrespective of the state of the activity.
   
2. Database modules for storing and retrieving  information for search provider and reports

3. Different Activities.

4. Broadcast receivers for checking the bluetooth status.


Future enhancement:
===================

1. Database back up to the cloud periodically.
2. Graphs to give the sale trends.



