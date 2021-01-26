# Awards

#### Author: [Ariso Okanga](https://github.com/Arisodee)

## Description
This web application allows users to post their projects and have them reviewed by their peers as well as rate and review projects posted by others.

A user will be able to:

1. Sign up and log in
2. View projects posted by other users
3. Post projects for rating and review
4. Rate and review a project
5. View and edit their profile
6. Access data from this application using API endpoints


| Behavior            | Input                         | Output                        | 
| ------------------- | ----------------------------- | ----------------------------- |
| Login	if already have an account |if you dont have , click on the sign up link and fill the form  | If login is successful, user is navigated to the home page | Click on `Review` | navigated to where you can write a review | Signs In/ Signs Up |
| Edit profile | On the account link, click on the   profile to update| Redirected to the profile page |
| Click on profile | Redirects to the profile page | User adds bio and profile picture |
|Add a new project|Click on the add project icon to be redirected to the new post form| Post is rendered on the home page
| Click on log Out in the accounts| Redirects to the login form | Logs out user  |



### Link to Live Site 
- [Awards](https://ariso-awards.herokuapp.com/)


## Technologies Used
- Python 3.6
- Django MVC framework
- HTML, CSS and Bootstrap
- JavaScript
- Postgressql
- Heroku

### Prerequisite
This project requires a prerequisite understanding of the following:
- Django Framework
- Python3.6
- Postgres
- Python virtualenv

## Setup and installation

#### Clone the Repository
####  Activate virtual environment
Create and activate virtual environment using python3.6 as default handler
    `python3.6 -m venv virtual && source virtual/bin/activate`
####  Install dependancies
Install dependancies that will create an environment for the app to run `pip3 install -r requirements.txt`
####  Create the Database
    - psql
    - CREATE DATABASE awards;
####  .env file
Create a file named`.env`  and copy paste the following filling-in where appropriate:
```
SECRET_KEY='nzq3mylg3#%gd892-fzj@nv%5dr12d33bzzse_&5_zt#l-@(4b'
DEBUG=True
DB_NAME='awards'
DB_USER='<your database username>'
DB_PASSWORD='<password to your database>'
DB_HOST='127.0.0.1'
MODE='dev'
ALLOWED_HOSTS='.localhost', '.herokuapp.com', '.127.0.0.1'
DISABLE_COLLECTSTATIC=1
```
#### Run initial Migration
python3.6 manage.py makemigrations instagram
python3.6 manage.py migrate

#### Run the app
python3.6 manage.py runserver
Open terminal on localhost:8000

## Known bugs
No known bugs at the moment

## Support and contact details
Incase you come across errors, have any questions, ideas ,concerns, or want to contribute to the application, feel free to reach me at : arisodee@gmail.com

### License

* LICENSED UNDER  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](license/MIT)