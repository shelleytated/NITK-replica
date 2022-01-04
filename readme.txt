Assignment-4
Replica of https://www.nitk.ac.in/

REQUIREMENTS:
1) Flask
2) Python
3) SQLAlchemy


Technology used:

FRONT END:
1) HTML5
2) CSS3
3) BOOTSTRAP
4) JAVASCRIPT


BACKEND:
Python FLASK Framework

DATABASE:
SQLAlchemy- A python SQL toolkit


Within nitk_cse we have 3 folders : 
    static - containing images, scripts and stylesheets
    templates - containing HTML pages
    __pycache__ : containing python logs.


Nitk_cse also contains 5 files : 
    __init.py__ : Python file contains various flask library imports.
    forms.py : Python file contains all forms displayed in HTML.
    models.py : Python file contains all database models(i.e. tables)
    routes.py : Python file contains all routing information from forms to database.
    site.db : The SQL Database binary file.

FLOW:
Front_page.......>Academics........> Departments........>CSE
CSE_Home.......>NEWS( CRUD operations )
./admin.......> add news and events
       .......> add research area
        ......> add professors
       .......> add research and development project
       ........> add consultancy
   
               

EXPLAINING DATABASE:
In our Database we have total 13 tables
using SQLAlchemy we have performed different CRUD operations
For example, on the nitk-cse webpage we can add, delete or upadte recent news.

#to run locally:
1) Download all the dependencies mentioned in requirements.txt file
2) start run.py file using python from powershell, it will generate a local web address for our website
3)In your browser, enter the above address which will direct to main homepage


