Bus ticket Reservation
The given C++ code implements a simple program for a bus ticket booking system. Here's a summary of the code:


cust_name: Manages customer details like name, phone number, and prompts users to input this information.
station: Inherits from cust_name and handles destination selection, providing information about different travel routes and ticket booking options.
reciept: Manages receipt details such as customer name, booked destination, payment details, and displays a receipt.
Functionality:

cust_name::get_detail(): Collects customer information like name and phone number.
station::dest_sel(): Allows the user to select a destination, providing details about the route and ticket options.
reciept::get_detail(): Gathers information from cust_name and station objects to create a receipt.
reciept::Display_detail(): Displays the receipt with customer details, booked destination, and payment information.
Main Function (main()):

Creates instances of cust_name, station, and reciept.
Invokes methods to gather user input, select destinations, generate a receipt, and display it.
Runs a loop allowing two iterations of the ticket booking process.
This program structure handles a basic ticket booking system for a bus station. Users can input their details, select a destination, choose ticket classes, and receive a receipt displaying booking information.
