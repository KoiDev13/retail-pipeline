# Note of usage  

- File csv: replace � is £. Replace by empty  

- [Dbt cli not running](https://forum.astronomer.io/t/dbt-on-airflow-astronomer/1265)  
- [Dash board](http://localhost:3000/dashboard/1-koi-retail)  
- [Dbt fix target path](https://github.com/dbt-labs/dbt-core/issues/6882)

## Commonly used command  

### Astro CLI  

- `astro dev bash`
- `astro dev start`
- `astro dev restart`

### Airflow CLI  

- `airflow tasks list retail`
- `airflow tasks test retail <task-id> 2023-01-01`

### DBT CLI  

- `dbt deps --profiles-dir /usr/local/airflow/dbt/`  
- `dbt run --profiles-dir /usr/local/airflow/dbt/`  

### Soda CLI  

- `soda scan -d retail -c include/soda/configuration.yml include/soda/checks/report/*`  
