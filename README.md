# DRF (Django Rest Framework)

Installation:
  
  Step 1: Clone the repo 
          
    git clone  https://github.com/VishDroid-dev/DRF.git
          
  step 2: Create a virtualenv
  
  For windows:
          
    pip install virtualenv
    python -m virtualenv venv
    .\venv\Script\activate
          
  For Linux:
  
    pip install virtualenv
    virtualenv venv
    source venv/bin/activate
            
  Step 3: Install the required dependencies 
          
    pip install -r requirements.txt
  
  Step 4: Make migrations and migrate for create tables and columns
          
    python manage.py makemigrations
    python manage.py migrate
  
  Step 5: Test Server is running
          
    python manage.py runserver
   
