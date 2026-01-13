## docker-compose.yml

This is the docker-compose.yml file used to spin up docker containers on my home lab. The following containers are created when this docker-compose file is run:

- cloudflared
- unifi
- openvpn
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
  
Spin up the containers:

```
docker-compose up -d
```

Stop all containers:

```
docker-compose down
```

Update all images:

```
docker-compose pull
```
