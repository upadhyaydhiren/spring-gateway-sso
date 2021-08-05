# Keycloak Docker

Use following command for start docker as auth server

```docker
docker run -d --name keycloak -p 8888:8080 \
   -e KEYCLOAK_USER=spring \
   -e KEYCLOAK_PASSWORD=spring123 \
   jboss/keycloak
```