# Docker Compose for Wildfly (running RBAC Management Service) + Postgres

## Running instructions

	> docker network create dockerrbacauthservicescomposed_postgres-rbac

Setup network

	> docker-compose up -d

The interface should be available at:

	http://localhost:8444

Default login: rbactester1
Default password: Changeit!
