# odoo_docker_dev_project

Tools for build a local odoo dev environnement fast and clean

Fill .env file with `PROJECT_NAME` and `ODOO_VERSION`

`docker-compose -f docker-compose-tools.yml up`

`docker-compose -f docker-compose-odoo.yml up`


You have
- Odoo on `PROJECT_NAME.localhost`
- PgAdmin on `pgadmin.localhost`
- Mailcatcher on `mailcatcher.localhost`