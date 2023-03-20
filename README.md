# docker-homeserver
Docker compose file to start your own home server with Jellyfin, Nextcloud, hardware and network speed monitoring.

.env file should look like this
```yml
UPUID=<USER_UID>
UPGID=<USER_GID>
MEDIA=<FOLDER_FOR_TORRENT_NEXTCLOUD_AND_MEDIA>
TZ=<COUNTRY/CITY>
DOMAIN=<DOMAIN>
USERNAME=<MARIADB_USERNAME>
MARIADB_PASSWORD=<MARIADB_PASSWORD>
MARIADB_ROOT_PASSWORD=<MARIADB_ROOT_PASSWORD>
SUBDOMAINS="jellyfin,nextcloud"
EMAIL=<EMAIL@EMAIL.DOM>
NETDATA_CLAIM_TOKEN=<NETDATA_CLAIM_TOKEN>
CLOUDFLARE_API_KEY=<CLOUDFLARE_API_KEY_FOR_CLOUDFLARE_DDNS>
```