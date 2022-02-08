# Raspberry Docker Config

Configuración para montar en tu Raspberry PI los contenedores imprescindibles.

<img src="https://upload.wikimedia.org/wikipedia/commons/d/d1/Raspberry_Pi_OS_Logo.png"/>

## Requerido

Necesario tener instalado [docker](https://docs.docker.com/engine/install/) y [docker-compose](https://docs.docker.com/compose/install/).

## Usage

```
docker-compose -f app.yml up -d
```

## Images

Las imagenes que se utilizan:

- [bazarr](https://hub.docker.com/r/linuxserver/bazarr) - Bazarr is a companion application to Sonarr and Radarr. It can manage and download subtitles based on your requirements. You define your preferences by TV show or movie and Bazarr takes care of everything for you.
- [calibre](https://hub.docker.com/r/linuxserver/calibre-web) - Calibre-web is a web app providing a clean interface for browsing, reading and downloading eBooks using an existing Calibre database. It is also possible to integrate google drive and edit metadata and your calibre library through the app itself.
- [grafana](https://hub.docker.com/r/grafana/grafana) - The Open-Source observability platform
- [home-assistant](https://hub.docker.com/r/homeassistant/raspberrypi4-homeassistant)
- [influxdb](https://github.com/terjesannum/docker-influxdb-arm32) - InfluxDB is a time series database built from the ground up to handle high write and query loads. InfluxDB is meant to be used as a backing store for any use case involving large amounts of timestamped data, including DevOps monitoring, application metrics, IoT sensor data, and real-time analytics.
- [jackett](https://hub.docker.com/r/linuxserver/jackett) - Jackett works as a proxy server: it translates queries from apps (Sonarr, SickRage, CouchPotato, Mylar, etc) into tracker-site-specific http queries, parses the html response, then sends results back to the requesting software. This allows for getting recent uploads (like RSS) and performing searches. Jackett is a single repository of maintained indexer scraping & translation logic - removing the burden from other apps.
- [qbittorrent](https://hub.docker.com/r/linuxserver/qbittorrent) - The Qbittorrent project aims to provide an open-source software alternative to µTorrent. qBittorrent is based on the Qt toolkit and libtorrent-rasterbar library.
- [radarr](https://hub.docker.com/r/linuxserver/radarr) - Radarr - A fork of Sonarr to work with movies à la Couchpotato.
- [readarr](https://hub.docker.com/r/linuxserver/readarr) - Readarr - Book Manager and Automation (Sonarr for Ebooks)
- [sonarr](https://hub.docker.com/r/linuxserver/sonarr) - Sonarr (formerly NZBdrone) is a PVR for usenet and bittorrent users. It can monitor multiple RSS feeds for new episodes of your favorite shows and will grab, sort and rename them. It can also be configured to automatically upgrade the quality of files already downloaded when a better quality format becomes available.
- [tautulli](https://hub.docker.com/r/linuxserver/tautulli) - Tautulli is a python based web application for monitoring, analytics and notifications for Plex Media Server.
- [telegraf](https://hub.docker.com/_/telegraf) - Telegraf is an open source agent written in Go for collecting metrics and data on the system it's running on or from other services. 

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)