# Cloud infrastructure as data in PostgreSQL

[IaSQL](https://iasql.com) is open-source software that treats infrastructure as data by maintaining a 2-way connection between a cloud account and a PostgreSQL database.

## ⚡️ Try out IaSQL

To [connect your AWS account](https://iasql.com/docs/aws) to a PostgreSQL database running locally generate AWS credentials, make sure docker is installed, and run:

```bash
docker run -p 9876:9876 -p 5432:5432 --name iasql iasql/iasql
```
