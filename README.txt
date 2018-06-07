

Software Design Document for Online Shopping
Introduction
In today’s society, online shopping has adapted to the fast-paced lifestyle, making customers enjoy the convenience of choosing and buying their favorite products at home. This system is based on, price comparison of retail stores at given location, and other related technologies. The foreground system achieves some functions including the user registration and login, checking and buying commodities, the shopping cart, the personal order management, the customer complaint and personal information management, etc. And the background system achieves functions including the administrator login, the commodities category management, the commodities management, the order management, the news and information management, and so on. When released, this system will be dynamic and interactive, and become an online shopping system which is operated easily to compare prices of different retail stores and has many other functions.
This design document mainly consists of State Machine/, Activity Diagrams, Class Design, and use case diagram. The main purposes of this design document are listed below.
1. Precise understanding of the requirements and constraints related with the programming language, and User Interface.
2. System decomposition into manageable units or modules 
3. Provide a basic outline of the User Interface of the online shopping.
Purpose 
The purpose of this project is to create a functional website for people to be able to both buy goods on low prices. Users of this website will be able to purchase goods to comparing prices of retail stores on their own choice. Website will supply them with an easy to use interface in order to purchase items. They will also be able to search available items, or by using a browsing function. Finally, a payment mechanism will be built in to allow the use of credit cards and checks to purchase items in order to abstract away one of the most difficult parts of setting up an on-line store. The website will be maintained and managed by administrators. The administrator will also be able to control customers and visitors actions.

Product Functions for Users 
Browse and Search: 
User should be able to browse through the entire items list by modifying location for retail stores.
In addition to providing the above mentioned search feature, user should also be able to search for a particular product
Shopping:  Add / remove items to their shopping cart/list
Customer should have the option to buy desired item(s) to comparing different retail stores prices.
Customer will have access to finalize product lists of items she wishes to buy and make the final payment 
The website should support all popular credit cards and make sure that the transaction happens securely.
 System Analysis 
1. Use cases 

Activity Flow associated with a user and service providers
2. Class Diagram
The following classes are used to design an online shopping mall. A class diagram is used to represent the relationship between the classes in a Unified Modeling Language (UML).

Customer Class: The Customer class is used to store the details of all the users. It is used to create a new user or help an existing user login. There are two types of users: admin and a normal user. Every user can place an order or search for a product. The admin can add and delete products as well. 
Order Class: The order class contains the details of the placed order. This class is used to place or delete an order. The order class is notified when an order is placed or deleted by a user.
Product Class: The product class contains the details of the products in the online shopping. This class will be notified when the user searches for a product.
Account Class: The Account class contains the details of the user Account in the online shopping. This class will be notified when the user checkout for a billing.
Retail Store Class: The Retail Store Class contains the details of the all retail stores which sell their product in the online shopping. This class will be notified when the user search for the retail store and select retail store.






