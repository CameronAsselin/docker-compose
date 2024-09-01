## docker-compose.yml

This is the docker-compose.yml file used to spin up docker containers on my home lab's raspberry pi4. The following containers are created when this docker-compose file is run:

- Homer
- Pihole
- Unbound
- Plex
- Kavita
- Audiobookshelf
- qBittorrent
- Prowlarr
- Flaresolverr
- Sonarr
- Radarr
- Handbrake
- Calibre

The following networks are created for the pihole + unbound recursive DNS server:

- pihole-unbound-macvlan
- pihole-bridge

To run the file using docker-compose OR update running containers in place, navigate to the directory the docker-compose.yml file is in:

```
docker-compose up -d
```

To stop and delete all containers and networks using docker-compose, navigate to the directory the docker-compose.yml file is in:

```
docker-compose down
```
