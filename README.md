Entorno Local para Desarrollo de microservicios.

Se genera una instancia de:

MongoDB
PostgreSQL
Keycloak

Tener instalado DOCKER y DOCKER-COMPOSE.

Crear la red network en DOCKER:

`docker network create backend`

Ejecutar YAML:

`docker-compose -f docker-compose.yml up -d`

Usuarios de PGADMIN

`User: pgadmin4@pgadmin.org`
`Password: admin`

NOTAS
Las imagenes ya estan en dockerhub
Para Keycloak se levanta por default:
*realm = rmteacherapp
*role = roleRmUserPrincipal (necesario para generar usuarios principales).

