### rebuildearth.org Website
Rebuild Earth Disaster Management , Awareness and Alertness Platform

# Quick Run !

### for production env - copy the .env.sample contents to .env and then update the variable's based on server configs

### Run the website in a local env

- fork the project

- clone the project

  `git clone https://github.com/<username>/rebuidearth`

  (change the `<username>` with your username)

  `cd rebuidearth`
- create a virtual env and activate

  `virtualenv -p python3 venv`

  `. env/bin/activate`
- install requirements

  `pip install -r requirements.txt`
- Create a .env file and copy contents of .env.sample
  (`variables` for Django project settings)

  `touch .env`

  `cp .env.sample .env`
- make migrations

  `python3 manage.py makemigrations`

  `python3 manage.py migrate`
- run the server

  `python3 manage.py runserver`
