# Simple Sql Server Database on Docker using docker-compose

The purpose of this repository is to bring a simple example of a SQL Server Database using docker and docker-compose in order to allow people using linux or macos to use SQL Server

## Connect info
- host: `localhost`
- database/schema: `master`
- username: `SA`
- password: `Alaska2017`

#### Build the container
- On the root of this repo you can run `docker-compose build` in order to download and build all the necessary to lift the container

#### Lift the SQL Server container
- On the root this repor you can run `docker-compose up` to lift the container
- An alternative to this is `docker-compose up -d` so you can get the terminal control back

#### Down the SQL server container
- On the root this repor you can run `docker-compose down --remove-orphans` to down all the related containers

##### Credits
This comes from the Microsoft repo: https://github.com/microsoft/sql-server-samples