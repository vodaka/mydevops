# The environment for mydevops

## 1 python 2.7 and python virtual environment
	- pip install virtualenv virtualenvwrapper
	- add the following in the .bashrc or /etc/profile:
	    source /usr/local/bin/virtualenvwrapper.sh	
	- source ~/.bashrc or /etc/profile
	- mkvirtualenv env_name(env_name directory located in ~/.virtualenvs/)
	- workon env_name
	- deactivate
	- rm virtualenv env_name
	- lsvirtualenv
	- cpvirtualenv [source] [dest]
	- pip freeze > requirements.txt
## 2 MySQL Mongo Redis
	
	#apt-get install mysql-server
	#apt-get install redis-server
	#apt-get install mongodb
	
