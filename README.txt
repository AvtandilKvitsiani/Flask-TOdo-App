


# File Structure

- `app.py`: The main application file containing the Flask app setup and routes.
- `templates/`: Directory containing HTML templates for rendering pages.
  - `index.html`: Displays the list of ToDo tasks.
  - `form.html`: Form template for adding and editing ToDo tasks.
- `static/`: Static files such as CSS and images.
  - `style.css`: Custom styles for enhancing the visual appearance of the application.
  - `star_green.png`: Icon for indicating completed tasks.
  - `star_purple.png`: Icon for indicating uncompleted tasks.
- `venv/`: Virtual environment directory (automatically created when setting up the project).
- `todos.db`: SQLite database file storing ToDo tasks.
- `requirements.txt`: List of Python dependencies for the project.
- `README.md`: Documentation file providing instructions and information about the project.


# Explanation

- `app.py`: The main logic of the Flask application, including route definitions and database setup.
- `templates/`: HTML templates to structure the frontend of the application.
- `static/`: Holds static files like images for the frontend.
- `venv/`:  to isolate project dependencies.
- `todos.db`: SQLite database for ToDo tasks.
- `requirements.txt`: the Python dependencies needed to run the project.
- `README.md`: Documentation file providing guidance on running the application and understanding its structure.




Features: View ToDo List: Users can view a list of ToDo items with descriptions. 
Add ToDo: Users can add new ToDo items with a description. 
Edit ToDo: Users can edit existing ToDo items to update their descriptions. 
Mark as Completed/Uncompleted: Users can toggle the status of a ToDo item between completed and uncompleted. 
Delete ToDo: Users can delete ToDo items from the list. Status Indicators: Completed ToDo items are visually indicated with a green status. Uncompleted ToDo items are visually indicated with a red status. 
Responsive Design: The application has a responsive design for a better user experience on various devices. 
Navigation: Navigation links to add a new ToDo item. Dropdown Actions: Users can perform actions (Mark as Done/Undone, Delete) from a dropdown menu for each ToDo item. 
Form Validation: Form validation ensures that users provide a description when adding or editing a ToDo item.