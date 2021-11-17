# What was deployed into userprofile

| Name                 | Required | Type        | Default Value | Description                                   |
|----------------------|----------|-------------|---------------|-----------------------------------------------|
| PORT                 | No       | ENV         | 80            | The port that the API service will listen on. | => no
| CONFIG_FILES_PATH    | No       | ENV         | /secrets      | The base path for file based variables.       | => no
| SQL_USER             | Yes      | ENV or File | sqladmin      | The username for the SQL Server database.     | => ok
| SQL_PASSWORD         | Yes      | ENV or File |               | The password for the SQL Server database.     | => ok
| SQL_SERVER           | Yes      | ENV or File |               | The server name for the SQL Server database.  | => ok
| SQL_DBNAME           | Yes      | ENV or File | mydrivingDB   | The name of the SQL Server database.          | => ok
