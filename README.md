# compose-mysql-pgadmin

# MySql & PgAdmin powered by compose


## Requirements:
* docker >= 17.12.0+
* docker-compose

## Quick Start
* Clone or download this repository
* Go inside of directory,  `compose-mysql-pgadmin`
* Run this command `docker-compose up -d`


## Environments
This Compose file contains the following environment variables:

* `MYSQL_USER` the default value is **testName**
* `MYSQL_PASSWORD` the default value is **testPass**
* `MYSQL_ROOT_PASSWORD` the default value is **password**
* `PGADMIN_PORT` the default value is **5050**
* `PGADMIN_DEFAULT_EMAIL` the default value is **pgadmin4@pgadmin.org**
* `PGADMIN_DEFAULT_PASSWORD` the default value is **admin**

## Access to mysql: 
* `localhost:3306`
* **Username:** testName (as a default)
* **Password:** testPass (as a default)

## Access to PgAdmin: 
* **URL:** `http://localhost:5050`
* **Username:** pgadmin4@pgadmin.org (as a default)
* **Password:** admin (as a default)
