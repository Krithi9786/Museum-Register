# Museum-Register
# Project Description:
The CRUD (Create, Read, Update, Delete) application is a powerful and flexible web application built using Node.js, PHP and MongoDB. This application is designed to simplify the management of data by providing seamless operations to create, read, update, and delete records in a MongoDB database.“Timed entry and pre-booking procedures could be introduced to reduce the number of visitors in locations at the same time”.Admin is the primary user who can add/remove/update any details related to the system, update prices of the Museum tickets, View/Confirm/Cancel booking orders placed by Users, and so on.Admin can manage registered users, keep the records of users, etc.
Users can register and then book the tickets for the Museum, make payments, etc. Users can find detailed information about the Museum on the system after logging in.

# Technologies Used:
                Node.js
                PHP
                MongoDB 
                
# Prerequisties:
The software required to run the project are the following,

                1.Visual Studio Code : Download and install Visual Studio Code from the website.
                2.Node.js: Make sure you have Node.js installed on your machine.
                3.MongoDB: Install MongoDB on your machine or use a cloud-based MongoDB service.
                              
# Frontend Specifications:  
The frontend used for this project is HTML,CSS AND JavaScript.The frontend of this CRUD application is developed using EJS (Embedded JavaScript) as the templating engine. EJS  allows the dynamic rendering of HTML templates with embedded JavaScript code, providing a seamless integration between frontend and backend components.

# Backend Specifications:
The backend of this CRUD application is built using Node.js and Express.js, providing a robust and scalable server-side architecture. It utilizes MongoDB Atlas, a cloud-based database service, accessed through Compass, a GUI tool for managing MongoDB databases. This application simplifies data management by providing seamless CRUD operations on the MongoDB Atlas database.It interacts with the MongoDB Atlas database through the MongoDB Node.js driver, ensuring seamless connectivity and efficient data operations.

# Mongodb CRUD Operations:

                Create:user can enter their data.
             
                Read:entered data can be read.
             
                Update:if user wants to made correction it can be done.
             
                Delete:data can be easily deleted.
                         
 # How to run
 Clone the repository to your local machine using the following command:
 
                git clone https ://github .com/Krithi9786/Museum-Register/
                
 Install the necessary dependencies. For example, if you are using Node.js and npm, navigate to the project directory and run the following command:    
          
                npm install
                
  Set up a connection to your MongoDB database. This can be done by configuring the connection details in a separate file or directly in the code. Ensure you have the         necessary credentials (e.g., host, port, username, password) to connect to your MongoDB instance.

  Modify the code as needed to match your database connection settings. Look for sections of code that handle the MongoDB connection and update them accordingly.

  Start the web server,using:

                npm start
                
  Ensure the server starts without any errors. Access the application in your web browser by navigating to the appropriate URL.(e.g., http ://localhost:3000).
# Explanation for code:
  The provided code is written in HTML and uses a templating language to dynamically generate the web page content. Here's an explanation of the different parts:

# HTML Structure:
  The code begins with the standard HTML structure. It defines the document type, the HTML language, and includes the necessary metadata in the <head> section.

  The <body> section contains the main content of the page.

# Page Title and Heading:
  
 The <h1> element displays the title of the page, which is "Mongodb CRUD Example".

# Create Operation:
  The code checks if the user_id variable is present. If it is, the page displays an edit form. Otherwise, it displays a create form.

# Edit Form:
  If the user_id variable is present, the code displays an edit form. The form's action attribute specifies the endpoint to handle the form submission for updating a museum with the given user_id.

# Museum List:
  The code uses a loop ({{#each museum}}) to iterate over a list of museums.

  For each museum, it generates an <li> element containing the museum's list and booking user details. It also includes two links: "Edit" and "Delete". The "Edit" link       includes the user's _id as a query parameter (user_id={{this._id}}) to identify which book to edit. The "Delete" link includes the user's _id as a query parameter           (delete_id={{this._id}}). It also includes an onclick event to show a confirmation dialog before deleting the museum.

# Conclusion:
  This code demonstrates a basic web application that allows users to perform CRUD operations (Create, Read, Update, Delete) on a collection of museum details and user       details stored in a MongoDB database. It provides forms for creating new user details and editing existing ones,as well as displaying a list of museums and users with       options to edit or delete each museums and users.










