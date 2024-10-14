# Task Manager

## Project Description
The Task Manager is a web application built using Django and Python that allows users to efficiently manage their tasks. Users can create, update, delete, and organize tasks, making it easier to keep track of their responsibilities. This project aims to provide a user-friendly interface for task management, addressing the common challenges of organization and prioritization.

### Motivation
The motivation behind this project is to simplify task management for users who struggle with keeping track of their daily responsibilities. By providing an intuitive platform, we hope to enhance productivity and reduce stress.

### Problem Solved
This application solves the problem of task overload by allowing users to categorize and prioritize their tasks effectively. It also offers features like deadlines and reminders to help users stay on track.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## Installation
To install the Task Manager application, follow these steps:

## Installation
To install the Task Manager application, follow these steps: 
1. Clone the repository: ```sh git clone https://github.com/andresguaman0621/minicore_guiado.git ``` 
2. Navigate into the project directory: ```sh cd minicore_guiado ``` 
3. Create a virtual environment: ```sh python -m venv venv ``` 
4. Activate the virtual environment: On Windows: ```sh venv\Scripts\activate ``` On macOS/Linux: ```sh source venv/bin/activate ``` 
5. Install the required dependencies: ```sh pip install -r requirements.txt ``` 
6. Run database migrations: ```sh python manage.py migrate ``` 
7. Start the development server: ```sh python manage.py runserver ```

##Usage
Once the server is running, navigate to http://127.0.0.1:8000 in your web browser. You can create an account or log in to access your task management dashboard.
##Example Usage
Creating a Task: Click on "Add Task" and fill in the details.
Updating a Task: Click on the task you wish to update, make changes, and save.
Deleting a Task: Click on the delete icon next to the task.
##Features
Create, update, and delete tasksm users, projects
Fitering tasks by date
Deadline setting when creating tasks
##Contributing
Contributions are welcome! If you would like to contribute to this project, please fork the repository and submit a pull request with your changes. Follow these guidelines for contributions:
Ensure your code follows our coding standards.
Write tests for new features.
Update documentation as needed.
##License
This project is licensed under the MIT License - see the LICENSE file for details. Feel free to reach out if you have any questions or need further assistance!


