# Django-To-Do-List-with-User-Authentication
This is a simple to-do list application built with Django, which allows users to sign up, log in,log out and create to-do items. Users can also search for specific items by title or description, and delete items they no longer need.
## Features
- User authentication: users can sign up, log in, and log out.
- Create, read, update, and delete to-do items.
- Mark to-do items as completed or uncompleted.
- List all to-do items, either for the logged-in user.
- Search for to-do items by title.
- Delete to-do items individually.
- Responsive design.
## Getting started
To run this project locally, you need to have Python and Django installed on your machine. Then, follow these steps:
1. Clone this repository and navigate to the project directory:
    ### git clone https://github.com/yourusername/todo-list.git
    ### cd todo-list
2. Create a virtual environment and activate it:
    ### python -m venv env
    ### source env/bin/activate    (for Linux/Mac)
    ### env\Scripts\activate       (for Windows)
3. Install the project dependencies:
    ### pip install -r requirements.txt
4. Run the database migrations:
    ### python manage.py migrate
5. Create a superuser:
    ### python manage.py createsuperuser
6. Run the development server:
    ### python manage.py runserver
7. Access the application in your browser at http://localhost:8000/
## Usage
- Register for a new account or log in using an existing account.
- Once logged in, you will be redirected to the To-Do list page.
- To create a new to-do item, click on the "Add new" button and enter the task description.
- To view, update, or delete a to-do item, click on the respective buttons next to the item.
- To search for a specific to-do item, enter the search query in the search bar and click on the search button.
- To delete multiple to-do items, select the items using the checkboxes and click on the delete button.
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
## License
This project is licensed under the MIT License.

