OVERVIEW:
            This is a simple To-Do List web application built using Python and Django. 
            The application allows users to create an account, log in, add tasks, mark them as complete, and delete them once finished. 
            Each user can log in and retrieve their own task data.

FEATURES:

  User Authentication: Sign up, log in, and log out securely.

  Task Management:

                Add new tasks.

                Mark tasks as completed.

                Delete completed tasks.

  User-Specific Data: Tasks are stored separately for each user.

  Responsive UI: User-friendly interface for easy navigation.

INSTALLATION:

  Prerequisites:

    Ensure you have the following installed on your system:

    Python (version 3.11 or later recommended)

    Django

    Virtual Environment (optional but recommended)

SETUP:

  Clone the Repository:
  
                  git clone <repository_url>
                  cd todo-list-app

Create and Activate a Virtual Environment (Optional but recommended):

                python -m venv venv
                source venv/bin/activate  # On macOS/Linux
                venv\Scripts\activate     # On Windows

Install Dependencies:

                pip install -r requirements.txt
                
                Run Migrations
                
                python manage.py migrate

Create a Superuser (Admin Access, Optional):

                python manage.py createsuperuser

Follow the prompts to set up an admin account.

Run the Development Server:

                python manage.py runserver

Open your browser and go to:

                http://127.0.0.1:8000/

USAGE:

        Sign Up or Log In to access your tasks.
        
        Add Tasks using the input field and "Add" button.
        
        Mark Tasks as Completed when finished.
        
        Delete Tasks once they are no longer needed.
        
        Log Out securely when done.

Technologies Used:

            Frontend: HTML, CSS, JavaScript (if applicable)
            
            Backend: Python, Django
            
            Database: SQLite (default) or PostgreSQL/MySQL (optional)

Contribution:
            
            Create a new branch (feature-branch).
            
            Commit your changes.
            
            Push to your branch and create a pull request.

For any queries or support, feel free to reach out:

Email: sekar.gauthamraj@gmail.com

GitHub: [GitHub Profile](https://github.com/Sekar7780/)
