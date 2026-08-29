# Roboshop-shellscript-automation

Shell scripts for automating the deployment and configuration of the RoboShop e-commerce application.

# Repository Contents

The repository contains the following scripts to deploy and configure the application.

| Script | Description |
|---|---|
| 00.ec2-creation.sh |	Creates EC2 instances required for the application |
| 01.common.sh	| Common configuration and functions used by the scripts |
| 02.mongodb.sh |	Installs and configures MongoDB |
| 03.catalogue.sh |	Deploys the Catalogue service |
| 04.frontend.sh	| Deploys the Frontend service |
| 05.redis.sh	| Installs and configures Redis |
| 06.user.sh |	Deploys the User service |
| 07.cart.sh |	Deploys the Cart service |
| 08.mysql.sh	| Installs and configures MySQL |
| 09.shipping.sh | Deploys the Shipping service |
| 10.rabbitmq.sh |	Installs and configures RabbitMQ |
| 11.payment.sh	| Deploys the Payment service |
| 12.dispatch.sh | Deploys the Dispatch service |