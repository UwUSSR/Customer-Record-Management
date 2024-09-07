# Customer-Record-Management

This is a simple Customer Management System written in C. It allows you to manage customer records, including adding, viewing, modifying, and deleting records. The system maintains a list of customers and their respective phone numbers, usage, and total bills.

Features
-Add New Record: Input a customer's name, phone number, and usage to add a new record.
-View List of Records: Display all customer records in a tabular format.
-Modify Record: Update the usage for a specific customer using their phone number.
-View Payment: View the payment details for a specific customer using their phone number.
-Delete Record: Remove a customer record based on their phone number.

Limitations
The system can handle a maximum of 100 customer records.
Phone numbers and customer names are stored as simple strings with no validation checks.
Usage is assumed to be in minutes and the total bill is calculated at fixed rate

Future Enhancements
Add validation for phone numbers and names.
Implement persistent storage to save records between program runs.
Add error handling for user inputs and file operations.
