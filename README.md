# rebuildearth.org
rebuildearth.org website
### Rebuild Earth Disaster Management , Awareness and Alertness Platform

# Quick Run !

### Run the website in a local env

- fork the project

- clone the project

  `git clone https://github.com/<username>/rebuidearth`

  (change the <username> with your username)

  `cd rebuidearth`
- create a virtual env and activate

  `virtualenv -p python3 venv`

  `. env/bin/activate`
- install requirements

  `pip install -r requirements.txt`
- Creat a .env file and copy contents of .env.sample
  (variables for Django project settings)

  `touch .env`

  `cp .env.sample .env`
- make migrations

  `python3 manage.py makemigrations`

  `python3 manage.py migrate`

- run the server

  `python3 manage.py runserver`
