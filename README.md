# JWT-authentication-backend
Clone the repo JWT-authentication-backend
Install virtualenv by running follwing commands : 
    pip install pipenv
    pipenv shell
Then set up django in virtual env.
    pipenv install django
    pipenv install djangorestframework
    pipenv install djangorestframework-jwt
    pipenv install django-cors-headers
Enter in the directory by running the command: cd JWT-authentication-backend/
Run the command: python manage.py migrate
Run the command: python manage.py createsuperuser (this is to create a user to login/sigunp)
Run the command: python manage.py runserver (this command actually runs the django server)

You can test the json web token authentication by opening localhost:8000/token-auth/ in your web browser
