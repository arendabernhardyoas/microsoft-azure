# Microsoft Azure

** **

## Azure App Service 

### Create WordPress Website

Create Azure App Service resource from Azure Portal<br>
![azure-home](./images/azure-home.png)
Type “WordPress” on search services and marketplace box<br>
![azure-create-resource-1](./images/azure-create-resource-1.png)
![azure-app-service-1](./images/azure-app-service-1.png)
![azure-app-service-2](./images/azure-app-service-2.png)
![azure-app-service-3](./images/azure-app-service-3.png)
![azure-app-service-4](./images/azure-app-service-4.png)
![azure-app-service-5](./images/azure-app-service-5.png)
Type public url on web browser<br>
![azure-app-service-6](./images/azure-app-service-6.png)

** **

## Azure Virtual Machine

### Linux Ubuntu SSH connection

Create Azure Virtual Machine resource from Azure Portal<br>
![azure-home](./images/azure-home.png)
Choose and create “Ubuntu Server 20.04 LTS” from popular resources<br>
![azure-create-resource-2](./images/azure-create-resource-2.png)
![azure-vm-1](./images/azure-vm-1.png)
![azure-vm-2](./images/azure-vm-2.png)
![azure-vm-3](./images/azure-vm-3.png)
![azure-vm-4](./images/azure-vm-4.png)
![azure-vm-5](./images/azure-vm-5.png)
![azure-vm-6](./images/azure-vm-6.png)
Connect to virtual machine via SSH with public IP address<br>
Install web server Type public IP address on web browser<br>
![azure-vm-7](./images/azure-vm-7.png)
![azure-vm-8](./images/azure-vm-8.png)
![azure-vm-9](./images/azure-vm-9.png)
![azure-vm-10](./images/azure-vm-10.png)

** **

## Azure Database

### Create and remote PostgreSQL

Create Azure Database resources from Azure Portal<br>
![azure-home](./images/azure-home.png)
Type “Azure Database for PostgreSQL” on search services and marketplace box Select “Single server” for deployment option<br>
![azure-create-resource-1](./images/azure-create-resource-1.png)
![azure-sql-1](./images/azure-sql-1.png)
![azure-sql-2](./images/azure-sql-2.png)
![azure-sql-3](./images/azure-sql-3.png)
![azure-sql-4](./images/azure-sql-4.png)
![azure-sql-5](./images/azure-sql-5.png)
![azure-sql-6](./images/azure-sql-6.png)
![azure-sql-7](./images/azure-sql-7.png)
![azure-sql-8](./images/azure-sql-8.png)
Create firewall rule in connection security setting for allow public IP access<br>
![azure-sql-9](./images/azure-sql-9.png)
Firewall rule allow all public IP from `0.0.0.0` to `255.255.255.255` similar to `pg_hba.conf` remote connection address `0.0.0.0/0`<br>
Connection strings to connect the database<br>
![azure-sql-10](./images/azure-sql-10.png)
![azure-sql-11](./images/azure-sql-11.png)
![azure-sql-12](./images/azure-sql-12.png)

** **

## Monitoring Laboratorium

### Web App (PHP runtime stack)

Create Azure App Service resource from Azure Portal<br>
![azure-monitoring-labs-create-resource-1](./images/azure-monitoring-labs-create-resource-1.png)
Choose and create “Web App” from popular resources<br>
![azure-monitoring-labs-create-resource-2](./images/azure-monitoring-labs-create-resource-2.png)
![azure-monitoring-labs-web-app-1](./images/azure-monitoring-labs-web-app-1.png)
![azure-monitoring-labs-web-app-2](./images/azure-monitoring-labs-web-app-2.png)
![azure-monitoring-labs-web-app-3](./images/azure-monitoring-labs-web-app-3.png)
![azure-monitoring-labs-web-app-4](./images/azure-monitoring-labs-web-app-4.png)
On Deployment Center choose GitHub as source<br>
Authorize GitHub account to connect repository<br>
GitHub repository [here](https://github.com/arendabernhardyoas/monitoring-laboratorium)<br>
![azure-monitoring-labs-web-app-5](./images/azure-monitoring-labs-web-app-5.png)
![azure-monitoring-labs-web-app-6](./images/azure-monitoring-labs-web-app-6.png)
![azure-monitoring-labs-web-app-7](./images/azure-monitoring-labs-web-app-7.png)
![azure-monitoring-labs-github-1](./images/azure-monitoring-labs-github-1.png)
![azure-monitoring-labs-github-2](./images/azure-monitoring-labs-github-2.png)

### Web App (NodeJS runtime stack)

Create Azure App Service resource from Azure Portal<br>
![azure-monitoring-labs-create-resource-4](./images/azure-monitoring-labs-create-resource-4.PNG)
Choose and create “Web App” from popular resources<br>
![azure-monitoring-labs-create-resource-5](./images/azure-monitoring-labs-create-resource-5.PNG)
![azure-monitoring-labs-web-app-8](./images/azure-monitoring-labs-web-app-8.PNG)
![azure-monitoring-labs-web-app-9](./images/azure-monitoring-labs-web-app-9.PNG)
![azure-monitoring-labs-web-app-10](./images/azure-monitoring-labs-web-app-10.PNG)
![azure-monitoring-labs-web-app-11](./images/azure-monitoring-labs-web-app-11.PNG)
![azure-monitoring-labs-web-app-12](./images/azure-monitoring-labs-web-app-12.PNG)
On Deployment Center choose GitHub as source<br>
Authorize GitHub account to connect repository<br>
GitHub repository [here](https://github.com/arendabernhardyoas/monitoring-laboratorium/tree/nodejs)<br>
![azure-monitoring-labs-web-app-13](./images/azure-monitoring-labs-web-app-13.PNG)
![azure-monitoring-labs-web-app-14](./images/azure-monitoring-labs-web-app-14.PNG)
![azure-monitoring-labs-github-3](./images/azure-monitoring-labs-github-3.PNG)
![azure-monitoring-labs-github-4](./images/azure-monitoring-labs-github-4.PNG)

### PostgreSQL

Create Azure Database resources from Azure Portal<br>
![azure-monitoring-labs-create-resource-1](./images/azure-monitoring-labs-create-resource-1.png)
Type “Azure Database for PostgreSQL” on search services and marketplace box Select “Single server” for deployment option<br>
![azure-monitoring-labs-create-resource-3](./images/azure-monitoring-labs-create-resource-3.png)
![azure-monitoring-labs-postgresql-1](./images/azure-monitoring-labs-postgresql-1.png)
![azure-monitoring-labs-postgresql-2](./images/azure-monitoring-labs-postgresql-2.png)
![azure-monitoring-labs-postgresql-3](./images/azure-monitoring-labs-postgresql-3.png)
![azure-monitoring-labs-postgresql-4](./images/azure-monitoring-labs-postgresql-4.png)
![azure-monitoring-labs-postgresql-5](./images/azure-monitoring-labs-postgresql-5.png)
Create firewall rule in connection security setting for allow public IP access<br>
![azure-monitoring-labs-postgresql-6](./images/azure-monitoring-labs-postgresql-6.png)
![azure-monitoring-labs-postgresql-7](./images/azure-monitoring-labs-postgresql-7.png)
Firewall rule allow all public IP from `0.0.0.0` to `255.255.255.255` similar to `pg_hba.conf` remote connection address `0.0.0.0/0`<br>
Connection strings to connect the database<br>
![azure-monitoring-labs-postgresql-8](./images/azure-monitoring-labs-postgresql-8.png)
`psql` connection strings to remote the database<br>
`PHP` connection strings to update database table (Web App using PHP runtime stack)<br>
`NodeJS` connection strings to update database table (Web App using NodeJS runtime stack)<br>
Create database table<br>
![azure-monitoring-labs-postgresql-9](./images/azure-monitoring-labs-postgresql-9.png)

### Result

Type public url of Web App resource on web browser<br>
![azure-monitoring-labs-1](./images/azure-monitoring-labs-1.png)
![azure-monitoring-labs-2](./images/azure-monitoring-labs-2.png)
![azure-monitoring-labs-3](./images/azure-monitoring-labs-3.png)
![azure-monitoring-labs-4](./images/azure-monitoring-labs-4.png)
![azure-monitoring-labs-5](./images/azure-monitoring-labs-5.png)

** **

## Monitoring Vehicle

### Web App (NodeJS runtime stack)

Create Azure App Service resource from Azure Portal<br>
![azure-monitoring-vehicle-create-resource-1](./images/azure-monitoring-vehicle-create-resource-1.PNG)
Choose and create “Web App” from popular resources<br>
![azure-monitoring-vehicle-create-resource-2](./images/azure-monitoring-vehicle-create-resource-2.PNG)
![azure-monitoring-vehicle-web-app-1](./images/azure-monitoring-vehicle-web-app-1.PNG)
![azure-monitoring-vehicle-web-app-2](./images/azure-monitoring-vehicle-web-app-2.PNG)
![azure-monitoring-vehicle-web-app-3](./images/azure-monitoring-vehicle-web-app-3.PNG)
![azure-monitoring-vehicle-web-app-4](./images/azure-monitoring-vehicle-web-app-4.PNG)
![azure-monitoring-vehicle-web-app-5](./images/azure-monitoring-vehicle-web-app-5.PNG)
On Deployment Center choose GitHub as source<br>
Authorize GitHub account to connect repository<br>
GitHub repository [here](https://github.com/arendabernhardyoas/monitoring-vehicle)<br>
![azure-monitoring-vehicle-web-app-6](./images/azure-monitoring-vehicle-web-app-6.PNG)
![azure-monitoring-vehicle-web-app-7](./images/azure-monitoring-vehicle-web-app-7.PNG)
![azure-monitoring-vehicle-github-1](./images/azure-monitoring-vehicle-github-1.PNG)
![azure-monitoring-vehicle-github-2](./images/azure-monitoring-vehicle-github-2.PNG)

### PostgreSQL

Create Azure Database resources from Azure Portal<br>
![azure-monitoring-vehicle-create-resource-1](./images/azure-monitoring-vehicle-create-resource-1.PNG)
Type “Azure Database for PostgreSQL” on search services and marketplace box Select “Single server” for deployment option<br>
![azure-monitoring-vehicle-create-resource-3](./images/azure-monitoring-vehicle-create-resource-3.PNG)
![azure-monitoring-vehicle-postgresql-1](./images/azure-monitoring-vehicle-postgresql-1.PNG)
![azure-monitoring-vehicle-postgresql-2](./images/azure-monitoring-vehicle-postgresql-2.PNG)
![azure-monitoring-vehicle-postgresql-3](./images/azure-monitoring-vehicle-postgresql-3.PNG)
![azure-monitoring-vehicle-postgresql-4](./images/azure-monitoring-vehicle-postgresql-4.PNG)
![azure-monitoring-vehicle-postgresql-5](./images/azure-monitoring-vehicle-postgresql-5.PNG)
![azure-monitoring-vehicle-postgresql-6](./images/azure-monitoring-vehicle-postgresql-6.PNG)
Create firewall rule in connection security setting for allow public IP access<br>
![azure-monitoring-vehicle-postgresql-7](./images/azure-monitoring-vehicle-postgresql-7.PNG)
![azure-monitoring-vehicle-postgresql-8](./images/azure-monitoring-vehicle-postgresql-8.PNG)
Firewall rule allow all public IP from `0.0.0.0` to `255.255.255.255` similar to `pg_hba.conf` remote connection address `0.0.0.0/0`<br>
Connection strings to connect the database<br>
![azure-monitoring-vehicle-postgresql-9](./images/azure-monitoring-vehicle-postgresql-9.PNG)
`psql` connection strings to remote the database<br>
`NodeJS` connection strings to update database table (Web App using NodeJS runtime stack)<br>
Create database table<br>
![azure-monitoring-vehicle-postgresql-10](./images/azure-monitoring-vehicle-postgresql-10.PNG)
![azure-monitoring-vehicle-postgresql-11](./images/azure-monitoring-vehicle-postgresql-11.PNG)

### Result

Type public url of Web App resource on web browser<br>
![azure-monitoring-vehicle-1](./images/azure-monitoring-vehicle-1.PNG)
![azure-monitoring-vehicle-2](./images/azure-monitoring-vehicle-2.png)
![azure-monitoring-vehicle-3](./images/azure-monitoring-vehicle-3.PNG)
![azure-monitoring-vehicle-4](./images/azure-monitoring-vehicle-4.PNG)
![azure-monitoring-vehicle-5](./images/azure-monitoring-vehicle-5.PNG)
![azure-monitoring-vehicle-6](./images/azure-monitoring-vehicle-6.PNG)
![azure-monitoring-vehicle-7](./images/azure-monitoring-vehicle-7.PNG)


** **

