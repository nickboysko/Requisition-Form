# Requisition-Form
The system allows employees to submit requests for items they need for their work, which are then reviewed and approved or denied by department heads. It integrates several technologies to provide a robust and user-friendly experience

Key Components

User Interface (UI):

HTML/CSS/Bootstrap: The front-end is built using HTML for structure, CSS for styling, and Bootstrap for responsive design. This ensures a clean, user-friendly interface that works well on both desktop and mobile devices.

Client-Side Functionality:

JavaScript: JavaScript is used for dynamic interactions and client-side validations. It enhances user experience by providing real-time feedback and enabling asynchronous operations, such as submitting requests without reloading the page.

Server-Side Processing:

Java: The backend of the application is developed in Java. It handles business logic, processes user requests, and interacts with the database.

Hibernate: Hibernate is employed for ORM (Object-Relational Mapping), simplifying the database interactions. It maps Java objects to database tables and manages CRUD (Create, Read, Update, Delete) operations.

Database Management:

SQL: SQL is used to define and manipulate the database schema and perform data operations. The database stores user information, request details, and approval statuses.

Functionality:

Employee Login: Employees can log in to the system using their credentials. The login process is typically secured with authentication mechanisms to protect user data.

Request Submission: After logging in, employees can submit requests for items. They can specify the item details, quantity, and any additional information needed.

Request Review: Department heads have access to a separate interface where they can review pending requests. They can approve or deny each request based on criteria like necessity and budget constraints.

Status Tracking: Employees can track the status of their requests to see if they have been approved, denied, or are still under review.

Vendor Rating: Users can rate the vendors for future use

Login: Employees and department heads log in with their credentials using google authentication

![loginPage](https://github.com/user-attachments/assets/b2c03a47-7142-454c-a547-8569a2869ff5)

Manage Users that are allowed in the application as well as give them different permission levels

![manageUsers](https://github.com/user-attachments/assets/409eb71d-822a-4bd9-bcc7-c97e7597fb51)
![manageUsersEdit](https://github.com/user-attachments/assets/52757dfc-c75f-4f91-843f-566c1095d35a)

Requests are displayed in a list on the home screen of the page. You can sort these requisitions by status or date

![requisitionList](https://github.com/user-attachments/assets/430731a9-4d6e-4200-968f-654ec7d8aead)

Requisitions can be edited or viewed depending on the users permission level. As well as the ability to create a PDF of the request

![requisitionEdit](https://github.com/user-attachments/assets/7e07b8c3-205c-4903-ab9c-1417bf444845)
![requisitionView](https://github.com/user-attachments/assets/9836146e-4004-40fa-857d-07fd9dc13d74)
![requisitionPDF](https://github.com/user-attachments/assets/c18bda2e-4a70-4f03-86ad-46984ec73656)

Past Vendors are displayed in a list form showing various information including the rating if a vendor needs to be rated still

![vendorList](https://github.com/user-attachments/assets/6b5e54e3-5fe8-41a5-bef5-ea9c799c2ccc)

Users can edit and view vendors based on their permission level. Users can see a vendors details, locations, contacts, reviews and past requisitions

![vendorEdit](https://github.com/user-attachments/assets/037bc0f5-9a31-4d03-9ecd-968496300c54)
![vendorView](https://github.com/user-attachments/assets/87113ce7-cf99-4a3f-b6bd-a5cb72ad763c)

Users also have the ability to rate venbdors based on their experience

![reviewVendor](https://github.com/user-attachments/assets/3b97f586-df61-4084-837f-a7895d3d42c0)
