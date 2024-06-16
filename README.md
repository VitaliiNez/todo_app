# Project Description: ToDo App

## Overview

This project is a web-based ToDo application that allows users to manage their tasks efficiently. The application provides functionalities to add, remove, edit tasks, filter tasks by status (Completed, Active, All), and display error messages when necessary. Error messages disappear automatically after 3 seconds. The project is built using React, TypeScript for type checking, Context API and useReducer for state management, and includes error handling. The application interacts with a server to persist tasks.

## Technologies Used

The ToDo app is built using modern web technologies to ensure a responsive and engaging user experience. The key technologies utilized are:

- **React:** Used for building the user interface. Components are created to manage different parts of the application.
- **TypeScript:** Provides static type checking to improve code quality and development experience.
- **Context API:** Used for managing the state globally within the application.
- **useReducer:** Used for handling state transitions in a predictable manner.
- **CSS:** Used for styling the application to create a visually appealing user interface.

## How to Use the Application

1. **Start the Application:** Open the app in a web browser. You will see an input field to add new tasks and a list of existing tasks.
2. **Add a Task:** Enter a task in the input field and press Enter. The task will be sent to the server and added to the list. If the input is empty, an error message will be displayed for 3 seconds. If there is a network issue, an error message will be displayed indicating that the task could not be added.
3. **Remove a Task:** Click the "Remove" button next to a task to delete it from the list and the server.
4. **Edit a Task:** Double-click on a task to enable editing. After making changes, press Enter to save. If the input is empty, the task will be automatically deleted. The updated or deleted task will be sent to the server. If there is a network issue, an error message will be displayed indicating that the task could not be updated or deleted.
5. **Filter Tasks:** Use the filter options (Completed, Active, All) to view tasks based on their completion status.
6. **Error Handling:** Error messages are shown for various conditions such as empty input, network issues while adding, removing, or updating tasks. These messages disappear automatically after 3 seconds.

## Running the Project Locally

To run the ToDo app project locally, follow these steps:

1. **Clone the Repository:**
   `git clone https://github.com/VitaliiNez/todo_app.git`
2. **Navigate into the Project Directory:**
   `cd todo_app`
3. **Ensure Node.js Version:**
   The project requires Node.js version 14.21.3 to run. You can check your Node.js version with:
   `node -v`
   If necessary, use a version manager like [nvm](https://github.com/nvm-sh/nvm/) to install and switch to the correct version.
4. **Install Dependencies:**
   `npm install`
5. **Run the Project:**
   `npm start`

You can now use the ToDo App locally in your browser.

To access the live site, visit [ToDo App](https://VitaliiNez.github.io/todo_app/).
