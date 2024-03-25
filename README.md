
# Friendly App

## Local Development

1. Clone the repository.

   `$ git clone`

2. Activate the virtual environment for local development.

   `$ friendlyapp-env\Scripts\activate`

    * To Deactivate the virtual environment. `$ deactivate`

3. Change to the application directory.

   `$ cd friendly`

4. Install the required packages.

   `$ pip install -r requirements.txt`

5. Run the Database Migrations

   `$ py manage.py migrate`

    `$ py manage.py makemigrations friendlyapp`

9. Run the local server.

   `$ py manage.py runserver localhost:8000`
