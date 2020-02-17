# GLA University, 2020

## Contact Lists

Create a menu-driven program to emulate a Contact Lists Application. 
You might see such apps in smartphones, you are free to go ahead and take ideas
from your own contact applications.  

Your menu-driven program must look like: 
```
Welcome to DBC's Contact List App
Press 1 to add a new contact
Press 2 to view all contacts
Press 3 to search for a contact
Press 4 to delete a contact
Press 5 to exit program 
```

The 'Add a new contact menu'
```
You have chosen to add a new contact: 
Please enter the name of the Person
First Name: Divyansh
Last Name: Bhardwaj
Contact Number: 1234567891
Would you like to add another contact number? (y/n): y
Contact Number: 2365987415
Would you like to add another contact number? (y/n): n
Would you like to add email address? (y/n): y
Email Address: divyansh.bhardwaj@gla.ac.in
```
Information about the 'add a contact menu'
1. This program will store this `Person` as a type (you have to create a Person class).
That means this program uses a list of `Persons`.

```java
public class Person {
    // a field to store the first name
    // a field to store the last name
    // a list to store multiple contact numbers (i.e a list of numbers)
    // a field to store the email address of the person 
}
```
---