# django_api

### Set Up

Install Virtual Box. If you are on windows, ensure Hyper-V is enabled.

# Dev

1. Navigate into the file directory
2. Execute `vagrant up` this will create the virtual environment where most of the work will be done (Ubuntu 64bit machine)
3. Once the machine is running, run `vagrant ssh` to gain access to the machine (Vagrant will take care of the usual parameters that go into `ssh`)
4. Execute `python manage.py runserver` to start the server
