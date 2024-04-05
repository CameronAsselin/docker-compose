###docker-compose.yml

This is the docker-compose.yml file used to spin up docker containers on my home lab's raspberry pi4. The following containers are created when this docker-compose file is run:

- Homer
- Pihole
- Unbound
- qBittorrent
- Prowlarr
- Flaresolverr
- Sonarr
- Radarr

The following networks are created for the pihole + unbound recursive DNS server:

- pihole-unbound-macvlan
- pihole-bridge
