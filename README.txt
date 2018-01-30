Django Client
==============
for "Django OAuth2 Server" : https://github.com/RichardKnop/django-oauth2-server#installation



Installation
=============

Clone the repository:

```
$ git clone https://github.com/A-Chornaya/Dj_client_oauth2.git
```

Create a virtual environment and install requirements:

```
$ virtualenv env
$ source env/bin/activate
$ pip install -r requirements.txt
```

Create the database:

```
$ python manage.py makemigrations client
$ python manage.py migrate
```

Configuration
=============

CLIENT_ID and CLIENT_SECRET set in the dj_client/settings.py

Default they set for "Django OAuth2 Server"



Start the project
=============

```
$ python manage.py runserver 8070
```

The "Django OAuth2 Server" start at the port 8080
