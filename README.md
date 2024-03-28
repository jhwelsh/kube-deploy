# Plex Media Server
# Steps used to deploy
   helm repo add plex https://raw.githubusercontent.com/plexinc/pms-docker/gh-pages
   helm show values plex/plex-media-server > values.yaml
   helm upgrade --install plex plex/plex-media-server --values values.yaml

