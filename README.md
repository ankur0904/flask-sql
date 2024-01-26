# To-Do List Web Application

## Description
This is a simple To-Do List web application that allows for all CRUD (Create, Read, Update, Delete) operations. It's built using HTML, Bootstrap, Python Flask, and SQLAlchemy as the database.

## Features
- Create new tasks
- View all tasks
- Update existing tasks
- Delete tasks

## Technologies Used
- **Frontend**: HTML, Bootstrap
- **Backend**: Python Flask
- **Database**: SQLAlchemy

## Setup and Installation
1. Clone the repository
2. Install the necessary packages (mentioned in requirement.txt)
3. On running it for the first time you might face an error regarding database for that:
4. Go to the path, where the app.py file is save
5. Open python terminal
6. Then execute these three commands consecutively( 1. from app import app,  2. from app import db,  3. db.create_all() )
7. Run the application
    

## Usage
1. To create a task, enter the task in the input field and click 'Submit'.
2. The tasks will be displayed in the task list.
3. To update a task, click the 'Update' button, modify the task, and confirm.
4. To delete a task, click the 'Delete' button.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


