Name: Tatheer Zahrah  
Roll No: BSCS-14-F25-58  
Course: Object Oriented Programming (OOP)  
Project Title: SheSafe – Women Safety Desktop Application  


 Description:
SheSafe is a Java Swing-based desktop application designed to enhance personal safety.  
It allows users to manage emergency contacts, report incidents, and receive motivational affirmations.  
The system is built using Object-Oriented Programming principles and includes an optional email alert system using Jakarta Mail.

 Key Features:
- Add and manage emergency contacts  
- View saved contacts  
- Report safety incidents  
- SOS emergency alert system  
- Daily motivational affirmations  
- GUI-based interactive dashboard  
- Email notification support (Jakarta Mail integration)


 Classes:

- Dashboard  
- LoginPage  
- Contact  
- ContactManager  
- Report  
- ReportManager  
- AffirmationSystem  
- UserSession (if used)  


 Constructors:

- Contact(String name, String email, String relation)  
- Report(String location, String description, String threatLevel)  
- ContactManager()  
- ReportManager()  
- AffirmationSystem()  
- Dashboard(String username)  


Methods:

- addContact()  
- getContacts()  
- addReport()  
- getReports()  
- getRandomAffirmation()  
- actionPerformed (Swing event handling)  
- showInputDialog()  
- setText()  


 Concepts Used:

1. Encapsulation  
2. Abstraction  
3. Object-Oriented Design  
4. Java Swing GUI  
5. Event-Driven Programming  
6. Java Collections Framework (ArrayList)  
7. Exception Handling  
8. File/Dependency Management  
9. Email Integration (Jakarta Mail API)  


 Email Functionality (Important Setup):

This project uses **Jakarta Mail API** for email-based features.

 Required JAR Files:
- jakarta.mail-2.0.1.jar  
- jakarta.activation-api-2.1.3.jar  

 Common Issue Fix:
If you get:: Faryal Ali
Roll No: BSCS-14-F25-34
Course: OOP
Project Title: MediShop – Pharmacy Management & E-Commerce System

Description:
This project is a modern Pharmacy Management and E-Commerce Desktop Application developed using Java Swing and Object-Oriented Programming concepts.

Classes:
- Product
- Medicine
- Supplement
- MedicalEquipment
- PersonalCare
- User
- Customer
- Admin
- ShoppingCart
- CartItem
- Order
- ProductRepository
- UserRepository
- LoginFrame
- CustomerFrame
- AdminFrame
- ProductCard
- SlideInCartPanel
- PasswordStrengthIndicator

Constructors:
Product()
Product(int productId, String name, String manufacturer, double price, int stockQuantity)

Medicine()
Medicine(int productId, String name, String manufacturer, double price, int stockQuantity, String dosage, String expiryDate, boolean requiresPrescription)

Supplement()
MedicalEquipment()
PersonalCare()

User()
User(int userId, String name, String email, String password, String phone)

Customer()
Admin()

Methods:
- addItem()
- removeItem()
- clearCart()
- login()
- register()
- searchProducts()
- addProduct()
- updateProduct()
- deleteProduct()
- getCategory()
- getDescription()
- calculateTotal()
- updateStock()

Operators:
Java does not support operator overloading like C++.
Instead:
- Method Overriding
- Method Overloading
- Polymorphism

Concepts:
1. Encapsulation
2. Inheritance
3. Abstraction
4. Polymorphism
5. Method Overriding
6. Constructor Overloading
7. Exception Handling
8. Event-Driven Programming
9. Java Collections Framework
10. GUI Concepts

GUI Components:
- JFrame
- JPanel
- GridBagLayout
- BorderLayout
- CardLayout
- JLayeredPane
- Java2D Graphics
- Anti-Aliasing
- Glassmorphism UI Design