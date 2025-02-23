# Metabase with MySQL Integration

## Overview
This project sets up Metabase with a MySQL database for real-time dashboards using Docker.

### What is Metabase?
Metabase is an open-source business intelligence tool that helps visualize and analyze data easily without requiring SQL expertise.

## Prerequisites
Ensure you have Docker and Docker Compose installed on your system.

## Running the Project
To start the services, run:
```sh
docker-compose up -d
```
This will spin up Metabase, MySQL, and phpMyAdmin.

To stop the services, run:
```sh
docker-compose down
```

## Accessing Services
- **Metabase**: [http://localhost:3001](http://localhost:3001)
- **phpMyAdmin**: [http://localhost:8080](http://localhost:8080)

## Setting Up Dashboards in Metabase
1. Open Metabase at [http://localhost:3001](http://localhost:3001)
2. Follow the setup wizard and connect to MySQL:
   - Host: `db`
   - Database Name: `mpay`
   - User: `user`
   - Password: `secret`
3. After setup, navigate to **New Dashboard** and add questions (queries or charts) using the connected MySQL database.

## Documentation
For detailed usage, refer to the official Metabase documentation: [https://www.metabase.com/docs/](https://www.metabase.com/docs/)

