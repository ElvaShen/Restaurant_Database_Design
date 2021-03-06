# Database Design for Restaurant Management
## Summary
Restaurant needs to manage table reservations, orders, menus, inventory,revenue and customer reviews. Our application will store data about customer reservations, orders, transactions, customer ratings, employee information, inventory and supplier information. Our application will be used daily to record transactions, revenue, keep track of employees, and allow the restaurant to coordinate suppliers to fill the necessary inventory to keep the restaurant running.

Swimlane Diagram
<img width="890" alt="swimlane diagram" src="https://user-images.githubusercontent.com/41976548/43547052-0082091a-958f-11e8-8569-84b6fdc8d2d5.png">

ER Diagram
<img width="847" alt="er diagram" src="https://user-images.githubusercontent.com/41976548/43547193-662e78c0-958f-11e8-9d03-673ebe27163c.png">

## Database Design
Following are our database design process:

* Conceptual Design
    - Create Entity Relationship Diagrams (ERD) for each user type
    - Build a Conceptual Data Model (CDM)
    - Define Business Rules, restrictions and requirements for database
* Logical Design
    - Transform CDM to a set of Third Normal Form (3NF) relations indicating all primary and foreign keys
* Physical Design
    - Create Procrocess Versis Entity Matrix
    - Create Composite Usage Map
    - Analyze key transactions
* Implementation
    - Write DDL statements to create database in SQL language
    - Implement indexing and clustering using the outcome of Physical Design
   
## Business Metrics
* Calculate daily revenue using histograms
<img width="656" alt="daily revenue" src="https://user-images.githubusercontent.com/41976548/43548823-c6b8294e-9593-11e8-91e3-96e2464dfe87.png">

* Calculate daily cost using histograms
<img width="772" alt="daily cost" src="https://user-images.githubusercontent.com/41976548/43548869-e81195f8-9593-11e8-974a-39dcf22059bf.png">

* Calculate total sales per item
<img width="683" alt="total sales per item" src="https://user-images.githubusercontent.com/41976548/43548897-fbfc2efc-9593-11e8-8e61-c5884f0a96be.png">
    
## Conclusion
This database model we structured covers the daily internal operation of most restaurants. It helps them to organize personnels to better serve customers in order to receive a satisfactory customer review; It also helps restaurant managers to coordinate with suppliers to keep track of the inventory cost in order to generate more profits.

