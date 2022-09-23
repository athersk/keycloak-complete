# keycloak-complete
in this repo contains only keycloack docker-compose file for postgress_keycloak-proxy_keycloak

##Terminal Work
Make directories as given below:

$ mkdir –p keycloak/conf

Now create one file inside conf directory name proxy.json // just copy and paste to file

Now create one direcorty for postgres data

$ mkdir postgres_data

Now Run The docker-compose file for keycloak, keycloak-proxy and postgres

$ docker-compose up -d

Now Access the Servicess Via Below Mentioned Linked

Elasticsearch : http://192.168.29.237:9200/

Kibana : http://192.168.29.237:5601/

Keycloack admin console : http://192.168.29.237:81/auth/admin

Machine IP May Vary
