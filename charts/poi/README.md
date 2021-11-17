# What have been done

| Name                    | Required | Type        | Default Value  | Description                                       |
|-------------------------|----------|-------------|----------------|---------------------------------------------------|
| WEB_SERVER_BASE_URI     | No       | ENV         | <http://0.0.0.0> | The url that API service web host will listen on. | => ??
| WEB_PORT                | No       | ENV         | 80             | The port that the API service will listen on.     | => no
| CONFIG_FILES_PATH       | No       | ENV         | /secrets       | The base path for file based variables.           | => no
| SQL_USER                | Yes      | ENV or File | sqladmin       | The username for the SQL Server database.         | => ok via secrets
| SQL_PASSWORD            | Yes      | ENV or File |                | The password for the SQL Server database.         | => ok via secrets
| SQL_SERVER              | Yes      | ENV or File |                | The server name for the SQL Server database.      | => ok
| SQL_DBNAME              | Yes      | ENV or File | mydrivingDB    | The name of the SQL Server database.              | => ok
| ASPNETCORE_ENVIRONMENT  | No       | ENV         | Development    | The ASP.NET hosting environment setting.          | => ok
