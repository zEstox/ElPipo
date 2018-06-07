# ElPipo
First Django project 

For ElPipo project you need a linux terminal

The step for installation of Django:

	1. sudo apt-get install python3.x
	2. sudo apt-get install python3-setuptools
	3. sudo apt-get install python3-pip
	4. pip3 install virtualenv
	5. virtualenv -p python3.x
	6. . /bin/activate
	7. python
	8. pip3 install Django==2.0.5
	9. exit()
	10. cd ..
	11. django-admin.py startproject ElPipoProject
	12. go to ElPipoProject... with cd command... cd ElPipoProject
	13. python manage.py runserver
	14. python manage.py makemigrations
	15. python manage.py migrate
	16. python manage.py createsupersuser
	17. python manage.py startapp core
  18. mv core/ ElPipoProject
  
  The step for installing MySQL:
  
  Yes ElPipoProject use MySQL, is cool... you can install the MySql now...
  
    1. mysql -u root -p
    2. show databases;
    3. use yourDatabase;
    4. show tables;
    5. select * from inYourDatabasTable;
    6. select database();
    
    But this can subistitute by QuerySets by Django directly... i m learning query... wait...
