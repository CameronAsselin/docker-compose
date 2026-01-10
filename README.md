## docker-compose.yml

This is the docker-compose.yml file used to spin up docker containers on my home lab. The following containers are created when this docker-compose file is run:

- cloudflared
- unifi
- homeassistant
- homarr
- jellyfin
- jellyseerr
- gluetun
- kavita
- calibre
- audiobookshelf
- qbittorrent
- prowlarr
- flaresolverr
- sonarr
- radarr
- apache-php
  
Run the file using docker-compose:

```
docker-compose up -d
```

Stop all containers using docker-compose

```
docker-compose down
```

Update all stopped containers using docker-compose:

```
docker-compose pull
```
