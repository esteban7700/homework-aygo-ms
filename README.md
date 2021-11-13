## Micronaut 3.0.2 Documentation

- [User Guide](https://docs.micronaut.io/3.0.2/guide/index.html)
- [API Reference](https://docs.micronaut.io/3.0.2/api/index.html)
- [Configuration Reference](https://docs.micronaut.io/3.0.2/guide/configurationreference.html)
- [Micronaut Guides](https://guides.micronaut.io/index.html)
---

## Feature testcontainers documentation

- [https://www.testcontainers.org/](https://www.testcontainers.org/)

## Feature kafka documentation

- [Micronaut Kafka Messaging documentation](https://micronaut-projects.github.io/micronaut-kafka/latest/guide/index.html)

## Feature http-client documentation

- [Micronaut HTTP Client documentation](https://docs.micronaut.io/latest/guide/index.html#httpClient)

## Feature hibernate-jpa documentation

- [Micronaut Hibernate JPA documentation](https://micronaut-projects.github.io/micronaut-sql/latest/guide/index.html#hibernate)

## Feature jdbc-hikari documentation

- [Micronaut Hikari JDBC Connection Pool documentation](https://micronaut-projects.github.io/micronaut-sql/latest/guide/index.html#jdbc)

## Configure dependencies repository aws artifactory

To configure dependencies artifactory with aws we created a lambda function to generate tokens and get acess to the aws
code artifactory

So you need to configure the `API_ARTIFACT_TOKEN` environment variable to get access to the aws lambda function and
retrieve the artifactory token
