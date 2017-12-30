# Udacity Item Catalog - Kannapiran

A simple web application which provides a list of items in categories and integrated third party user registration and authentication(Google and Facebook). Authenticated users have the ability to post, edit, and delete their own items.

## Set Up

1. Clone the project from respository.

2. Launch the Vagrant VM from inside the *vagrant* folder with:

`vagrant up`

Then access the shell with:

`vagrant ssh`

Then move inside the catalog folder:

`cd /vagrant/catalog`

Then run the database configuration using below command (to load with default values):

`python sampleitems.py`

Then run the application:

`python application.py`

After the last command you are able to browse the application at this URL:

`http://localhost:8000/`