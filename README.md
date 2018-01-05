Q1. Create a docker-compose file using v2 format that will create an nginx web server and postgres database container which can communicate successfully.

To bring container up run, 
```
docker-compose up -d
```

I have not configured NGINX to talk directly to Postgres, this requires using a postgres module.
Docker will provide an virtual network that allows containers to talk to each other.
I jumped into each container and was able prove connectivity to the other container.
