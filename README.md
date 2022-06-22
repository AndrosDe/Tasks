![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

Welcome,

This is the Code Institute student template for deploying your third portfolio project, the Python command-line project. The last update to this file was: **August 17, 2021**

## Reminders

In order to start have the database you have to:

### 1:
gitpod /workspace/Tasks (main) $ psql
psql (12.11 (Ubuntu 12.11-1.pgdg20.04+1))
Type "help" for help.

postgres=# CREATE DATABASE taskmanager;
CREATE DATABASE
postgres=# \c taskmanager;
You are now connected to database "taskmanager" as user "gitpod".
taskmanager=# \q

### 2:
gitpod /workspace/Tasks (main) $ python3
from taskmanager import db
db.create_all()

## Creating the Heroku app

When you create the app, you will need to add two buildpacks from the _Settings_ tab. The ordering is as follows:

1. `heroku/python`
2. `heroku/nodejs`

You must then create a _Config Var_ called `PORT`. Set this to `8000`

If you have credentials, such as in the Love Sandwiches project, you must create another _Config Var_ called `CREDS` and paste the JSON into the value field.

Connect your GitHub repository and deploy as normal.

## Constraints

The deployment terminal is set to 80 columns by 24 rows. That means that each line of text needs to be 80 characters or less otherwise it will be wrapped onto a second line.

-----
Happy coding!