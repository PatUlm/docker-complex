## Links

- https://travis-ci.com/
- [Amazon ECS Container Definitions](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/task_definition_parameters.html#container_definitions)
- [DockerHub Repositories](https://hub.docker.com/repositories)

## Operation

- *AWS Elastic Beanstalk (BS)*
- *AWS Elastic Container Service (ECS)*
- *AWS Elastic Cache* statt *Redis*
- *AWS Relational Database Service (RDS)* statt *Postgres*
- *AWS Virtual Private Cloud (VPC)*

*AWS Elastic Beanstalk* übergibt beim Betrieb von Containern diese an *AWS Elastic Container Service (ECS)*.
*AWS ECS* verwendet sogenannte *Task definitions*, welche die Instuktionen beinhalten, wie ein einzelner Container ausgeführt werden soll.
Diese sogenannten `Container Definitions` von *AWS ECS* sind in der `Dockerrun.aws.json` enthalten. `Dockerrun.aws.json` gehört zu *AWS BS*
