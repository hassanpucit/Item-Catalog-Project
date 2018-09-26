# Item Catalog

Project 4 of Udacity FSND

# Tools Required

1- Vagrant
2- Udacity Vagrantfile
3- VirtualBox

#Running the Project

In order to run this program you will need the following:

1- Install Vagrant and VirtualBox
2- Download the Vagrantfile from the Udacity Repo
3- Run `vagrant up` to run the virtual machine, then `vagrant ssh` to login to the VM
4- Run application with `python application.py` from within its directory
5- go to `http://localhost:8081` to access the application
6- for first time, you must add a category before adding an item

# JSON Endpoints
`/api/v1/catalog.json` - Returns JSON of all items in catalog
`/api/v1/categories/JSON` - Returns JSON of all categories in catalog