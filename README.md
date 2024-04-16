python_blockchain_app

A simple tutorial for developing a blockchain application from scratch in Python.

What is blockchain? How it is implemented? And how it works?
Please read the step-by-step implementation tutorial.

Instructions to run
Clone the project,

$ git clone https://github.com/satwikkansal/python_blockchain_app.git
Install the dependencies,

$ cd python_blockchain_app
$ pip install -r requirements.txt
Start a blockchain node server,

$ export FLASK_APP=node_server.py
$ flask run --port 8000
For windows users
set LANG=C.UTF-8
set FLASK_APP=node_server.py
flask run --port 8000
One instance of our blockchain node is now up and running at port 8000.

Run the application on a different terminal session,

$ python run_app.py
For windows users
set LANG=C.UTF-8
set FLASK_APP=run_app.py
flask run --port 8000
The application should be up and running at http://localhost:5000.
