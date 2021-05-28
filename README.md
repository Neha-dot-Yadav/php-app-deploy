# php-app-deploy

This project demonstrates how we can deploy a PHP app using Ansible.
It has four roles,
1. apache - which installs and starts the apache web server on centos machine.
2. mysql - which installs and starts mysql service on centos machine. It also creates a sample database and adds sample data for our php app in the database.
3. php - which installs php on centos machine deploys the sample php web app.
4. nginx - it installs nginx on centos machine and configures as a load balancer.
