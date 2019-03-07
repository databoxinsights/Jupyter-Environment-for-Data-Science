# Jupyter-Environment-for-Data-Science

## How to create a Jupyter Environment with Core Data Science Packages

### Step 1: Install pre-requisites

* pip install --upgrade pip
* pip install virtualenv
* pip install virtualenvwrapper-win


### Step 2: Create a directory for your virtualenv

* Navigate to the folder directory where you want the virtualenv installed 
* mkvirtualenv envname
* setprojectdir. # setting this make this the default directory for your virtualenv; easy to activate later. 
* pip list # you can see there are no currently installed packages

### Step 3: 

* dir # list the files in directory to make sure requirements.txt file is there. 
* pip install -r requirements.txt
* pip list # run this to see all newly installed libraries. Enjoy! 

### Step 4: 
* jupyter lab # launches a new python kernel in jupyter lab. 
* jupyter notebook #launhes a new python kernel in jupyer notebook. 

### Future Steps: 
* deactivate envname # to deactivate your virtualenv 
* workon envname # activates your virutualenv and navigates to your project directory automatically. 
