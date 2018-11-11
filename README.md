# INSTAGRAM CLONE
> Moringa school IP
[Live Link](https://not-instagram.herokuapp.com/)
## Description
This is a clone of the image sharing network, Instagram. 
Users can sign up login, view and post photos and follow other users.

## Author
### Xavier Kibet

## User Stories
1. Register and Sign in to the application.
2. Upload my pictures to the application.
3. See my profile with all my pictures.
4. Follow other users and see their pictures on my timeline.
5. Like or Save a picture and leave a comment on it.


## Setup and installation

#### Clone the Repo
    git clone https://github.com/reivhax/Not-Instagram 
    cd Not-Instagram
####  Activate virtual environment
create and acvite a virtual environment
    `python3.6 -m venv virtual && source virtual/bin/activate`
####  Install dependancies
Install dependancies that will create an environment for the app to run 
`pip install -r requirements.txt`
####  Create the Database
    - psql
    - CREATE DATABASE instaclone;
####  .env file
Create .env file and paste paste the following filling where appropriate:

    SECRET_KEY = '<Secret_key>'
    DBNAME = 'instaclone'
    USER = '<Username>'
    PASSWORD = '<password>'
    DEBUG = True
#### Run initial Migration
    python3.6 manage.py makemigrations instaclone
    python3.6 manage.py migrate
#### Run the app
    python3.6 manage.py runserver

## Technologies Used

- Python 3.6 and The Django framework
- HTML, CSS and Bootstrap
- JavaScript
- Heroku

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) file for details
