# docker-odoo
Docker Compose for running Odoo with PostgreSQL

## Containers
* Odoo
* PostgreSQL

## Installation
1. Configure the database user and password for postgres on  ./env/db.env
```
POSTGRES_USER=
POSTGRES_PASSWORD=
```
2. Set the same credentials for odoo on ./env/web.env
```
USER=
PASSWORD=
```
3. Run the containers
```
 docker-compose up 
```
4. Launch Odoo from your browser using the same port configured on compose file
```
 http://<host ip>:8069
```

