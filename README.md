# Keycloak Docker Swarm Examples

## Configuration: Keycloak, PostgreSQL and JDBC_PING

keycloak-cluster-jdbcping.yml creates a two keycloak instance cluster connected to a shared instance of PostgreSQL. The example uses JDBC_PING discovery protocol to find initial membership.

Run the example using the following command:
```
sudo docker stack deploy -c keycloak-cluster-jdbcping.yml keycloak
```

