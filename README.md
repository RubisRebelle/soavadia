# SOAVADIA

**SOAVADIA** is a transport business company that has a database to manage its employees, clients, travels...

The database contains much information such as the Clients' information, the employees of the company, the company's Vehicles, the departure and the destination of the trip, and much more.

## Model
This is the database model schema of this project
<p align="left">
  <img src="https://github.com/Herizoran/soavadia/tree/main/images/Soavadia_schema.jpg" />
</p>

## Prerequisites
* OS Windows (XP or Later), Linux, MacOs
* **PostgreSQL**


## Installation
- Open a command prompt or a PowerShell if you are on Windows, or Terminal if you are on Linux
- Run the command below, and enter the user's password.
``` sql
psql -U $user
```
- Once you are logged in, run this command
``` sql
\i path/soavadia.sql
```
The "path" is the directory where you put the ***soavadia.sql*** file

## Log in
- To log into the databasse, once you are logged into the user which contains the **soavadia** database, connect to the database by running this command

``` sql
\c soavadia;
```
## Requests
If you have any ideas to improve this database then feel free to <a href='https://github.com/Herizoran/soavadia/pulls'>ask for changes</a>!