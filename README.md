
# Web Forms with Flask, Docker, PyCharm, and MySQL

In this project i have created HTML forms to create new records, update records, and a small form that
has no fields other than a submit button to delete records.

### Note: 
This project is setup to have Docker Compose setup a python flask app and a mysql server that will load data from
the db/init.sql file the first time the database starts (note you will need to do a docker down by right clicking on
the compose file in pycharm docker service to reset the database if you make any changes to the sql statements
that load initially, it doesn’t run the init.sql each time you run your project, just each time docker-compose is run
from scratch). Then you need to create a flask framework to serve flask jinja template files and send http POST
requests to update, add new records, and delete.

## Dataset

Oscar data - [Oscar-male.csv](https://people.sc.fsu.edu/~jburkardt/data/csv/csv.html)

Use this to convert 100 records of the CSV file to an SQL insert:
https://sqlizer.io/#/

https://codebeautify.org/csv-to-sql-converter
this one works very well and doesn’t seem to have a limit.

You can view and edit your CSV data in excel before you convert it, so you limit it to 100 records and can rename
any fields, just save it as a CSV file.

## Submission

[Document](https://github.com/jasneekchugh/WebForms-with-Flask/blob/master/Project%20Document-Submission.pdf)
