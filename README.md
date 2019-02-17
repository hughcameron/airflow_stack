# An Airflow Docker Stack

`docker exec -it jupyter lab --allow-root --ip=0.0.0.0 --port=2000`

An example `.env` file with environment variables for docker-compose looks like:

``` env
AIRFLOW_DIR=/home/docker/airflow
AIRFLOW_EMAIL=myemail@gmail.com
AIRFLOW_USER=<dbuser>
AIRFLOW_PASSWORD=<dbpassword>
AIRFLOW__CORE__FERNET_KEY=<fernet_key>
POSTGRES_DIR=/home/docker/airflowdb
POSTGRES_DB=airflow
POSTGRES_PORT=5432
POSTGRES_USER=airflow
POSTGRES_PASSWORD=airflow
METABASE_DIR=/home/docker/metabase
WAREHOUSE_DIR=/home/docker/warehousedb
WAREHOUSE_DB=warehouse
WAREHOUSE_PORT=5040
WAREHOUSE_USER=<dbuser>
WAREHOUSE_PASSWORD=<dbpassword>
DOMAIN=example.com
IP_RANGE=192.168.66
TIMEZONE=GMT
```

See this Wikipedia list of [Valid Timezones](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones)