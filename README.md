# stickynote
A simple sticky note application
# Sticky Notes Application

## Table of Contents
1. [Project Overview](#project-overview)
2. [Description](#description)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Screenshots](#screenshots)
6. [Credits](#credits)

## Project Overview
🔛 Sticky Notes Application

## Description

The Sticky Notes Application is a robust web-based solution leveraging Django and Django REST Framework to implement a comprehensive note management system.
This application showcases the implementation of RESTful API endpoints for seamless CRUD (Create, Read, Update, Delete) operations, a cornerstone of modern web development paradigms.

Built on Django's powerful ORM (Object-Relational Mapping), the application ensures efficient database interactions and data persistence. 
The Django REST Framework facilitates the creation of a scalable API architecture, enabling smooth client-server communication through serialized data exchanges.

This project serves as an exemplar of best practices in web application architecture, demonstrating:

1. RESTful API design principles
2. Stateless client-server communication
3. Resource-based routing
4. HTTP method utilization for semantic operations

By exploring the intricacies of this application, I gained invaluable insights into the symbiosis between frontend interfaces and backend logic, the nuances of data flow in web applications, and the implementation of secure and efficient database operations.

This foundational knowledge is instrumental in mastering the complexities of full-stack web development and formed a solid basis for tackling more advanced concepts in distributed systems and microservices architecture as I will be showing in my next application.

## Installation
To run this project locally, follow these steps:

1. **Clone the Repository**
   ```pwsh
   git clone https://github.com/yourusername/sticky-notes.git
   cd sticky-notes
   
2. **Create a virtual environment**
   ```pwsh
   git clone https://github.com/yourusername/sticky-notes.git
   cd sticky-notes
   
3. **Install Dependencies
   ```pwsh
   pip install -r requirements.txt

4. **Apply Migrations
   ```pwsh
   python manage.py makemigrations
   python manage.py migrate

5. ##Run the Server
   ```pwsh
   python manage.py runserver

6. ###Usage
   After installing the project locally, you can use it as follows:

    ```Access the Application
      Open your web browser and go to http://127.0.0.1:8000.
      
      Create a New Note
      Click on the "New Note" button to create a new note. Fill in the title and content fields and click "Save".
      
      View Notes
      The home page lists all the notes. Click on a note's title to view its details.
      
      Edit a Note
      In the note's detail view, click on the "Edit" button to modify the note.
      
      Delete a Note
      In the note's detail view, click on the "Delete" button to remove the note.

7. Screenshots
   ## View existing notes
   
   ![View the notes](https://github.com/ayodejioju/stickynote/blob/main/screenshots/View_all_notes.png "Viewing exiting notes")

   ## Create or Edit Notes
   
   ![View the notes](https://github.com/ayodejioju/stickynote/blob/main/screenshots/Create_new_notes.png "Editing a note")
   
   ## Read a Notes
   
   ![View the notes](https://github.com/ayodejioju/stickynote/blob/main/screenshots/Read_note.png "Reading a note")

   
### 👨🏾‍💻 by [AyoDeji](https://github.com/ayodejioju)
