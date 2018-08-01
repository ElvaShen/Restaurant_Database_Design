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
    
## Future Potentials
We believe this succint yet efficient database model that we structured for Zillow.com will solve their current problems of high latency of the web searching and loading speed due to large database, which will lead to bad user experience. Furthermore, a high-integrity database model will be helpful for them to track, collect and analyze data along the time. This will optimize students' online housing searching experience, specifically for university apartment rental market. 

