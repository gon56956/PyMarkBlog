
~ What is PyMark Blog?

	PyMark Blog is a minimal blog application based on python flask framework.
	Markdown syntax is highly recommend for this blog system.

~ How to deploy?


	1. Intall Flask and markdown2
	pip install Flask
	pip install markdown2
	please refer to http://flask.pocoo.org/docs/0.10/installation/
	https://github.com/trentm/python-markdown2

	2. edit the configuration in the pymark.py file or
     export an PYMARK_SETTINGS environment variable
     pointing to a configuration file.
     change the blog name, and admin accout/password:
     eg:
     BLOGNAME = "PyMark BLog"
     USERNAME='admin'
     PASSWORD='admin'

	3. now you can run pymark:
	flask --app=pymark initdb
	flask --app=pymark run -h 0.0.0.0 -p 8000
	
	the application will greet you on
	http://localhost:8000/
	
	Login to Admin page and post a new blog :)
	http://localhost:8000/admin

~ Bug?

	Email me: Wenbinhk@gmail.com
	
	![alt tag](https://github.com/hacklogic/PyMarkBlog/blob/master/pymark.png)
