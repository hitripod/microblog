microblog
=========

A decently featured microblogging web application written in Python and Flask that I'm developing in my Flask Mega-Tutorial series that begins [here](http://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world).

Installation
------------

The tutorial referenced above explains how to setup a virtual environment with all the required modules.
 
The sqlite database must also be created before the application can run, and the `db_create.py` script takes care of that. See the [Database tutorial](http://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-iv-database) for the details.

Python 3.4.1
* pip install flask-login
* pip install flask-openid
* pip install flask-mail
* pip install flask-babel
* pip install guess_languag
* pip install https://bitbucket.org/spirit/guess_language/downloads/guess_language-spirit-0.5a4.tar.bz2
* pip install sqlalchemy-migrate
* pip install flask-migrate
* pip install flask-sqlalchemy

Running
-------

To run the application in the development web server just execute `run.py` with the Python interpreter from the flask virtual environment.

* python db_creat.py
* python db_migrate.py (optional)
* python db_upgrade.py
* python run.py
