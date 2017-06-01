# HTTPSWordpress
Docker Compose using HTTPS-PORTAL. The goal is to ship a wordpress solution with HTTPS using letsencrypt and auto renew.

#### Pre-Requisites
First of all, configure our DNS to point to the machine that you are running the script on

#### Environment Variables
- DOMAIN = Domain name for your website
- WORDPRESS_DB_PASSWORD = Your database password

#### Quick Start
`DOMAIN=<domain> WORDPRESS_DB_PASSWORD=<password> docker-compose up`
