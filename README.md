# ASP.Net Core Web API with Docker Compose, PostgreSQL and EF Core.
A simple ASP.NET Core sample web application using .Net Web Api Core and PostgreSQL with Docker support.Both the Web Applicaiton and the Postgres DB runs in container. Added Swagger support to interact with API’s resources.

## Prerequisites
1. [Docker](https://www.docker.com/)

##New steps
Project was changed to startup containers from VS2019.
seed.sql was changed to seed.txt to prevent sql error on start project

Navigate to https://localhost:32790/swagger/index.html

##Plans
And it would be greate to connect to postgrest database to view a data.

## Old Steps
1. `git clone https://github.com/rajvirtual/docker-aspnetcore-postgresql.git`

2. `cd docker-aspnetcore-postgresql`

3. `docker-compose build`

4. `docker-compose up`

5.  Navigate to http://localhost:8000/swagger


