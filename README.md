# NGINX reverse proxy server

An NGINX configuration sample for setting up reverse proxy to allow following services - 
- `http://X.X.X.X/plex`
- `http://X.X.X.X/radarr`
- `http://X.X.X.X/sonarr`
- `http://X.X.X.X/deluge`
- `http://X.X.X.X/` Default NGINX page

Highly scalable. Just keep adding more service-*.conf files.