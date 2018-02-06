# Dj_client_oauth2
Django Client
==============
Server example: "Dj_server_oauth2" :
https://github.com/A-Chornaya/Dj_server_oauth2.git



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

Set configuration in the dj_client/settings.py:
- CLIENT_ID
- CLIENT_SECRET
- AUTHORIZATION_URL
- TOKEN_URL

Default they set for "Dj_server_oauth2"



Start the project
=============

```
$ python manage.py runserver 8070
```

The "Dj_server_oauth2" start at the port 8080



Open in browser
=============
Go to http://127.0.0.1:8070/client/
You should see the index page, where you can log in with another server
You will redirect to the server, where you need log in (sign up) and agree with credentials
Then you will return to the client and see json with data from server