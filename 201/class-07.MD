# Domain Modeling
### ``https://github.com/codefellows/domain_modeling#domain-modeling``
- domain modeling is the process of creating a conceptual model in code for a specific problem. 
- this aricle talks about using constructors to create objects
- constructor functions should be captalized
- the 'new' keyword instantiates the object
- 'this' is a new keyword which assigns the key name of the object element
# From the Duckett HTML book:

## Chapter 6: “Tables” (pp.126-145)
- in HTML tables are written out row by row
- th is used for table headers and can be specified as either column or row header
- rowspan and colspan is used to span a row or column more than one cell in the table
- table can be broken down into a table head, table body and table foot
# From the Duckett JS Book:

## Chapter 3: “Functions, Methods, and Objects” (pp.106-144)
- a different way to create an object is using constructor notation:
```
const hotel = new Object();
hotel.name = 'Quay';
hotel.room = 40;
hotel.booked = 25;
```
- to update an object:
    - hotel.name = 'Park' 
        - use the name of the object, then . followed by the key name
- constructors are functions the create new Objects
    - constructor functions begin with a capital letter
    - they are called with the 'new' keyword followed by the function call; example
        ```
        const fancyHotel = new Hotel('Quay', 40, 25)
        ```
- use delete keyword to delete a property or method
    ```
    delete hotel.booked
    ```
- 