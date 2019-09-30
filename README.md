# MediaServer
Docker based mediaserver setup

## Config
Two config files are needed: `.env` and `docker-compose.yml`. For both of these files, a `*.example` file is provided.  
After Plex is up and running, the media folder listed in the override config still need to be added as libraries. 
More info on this can be found here [https://support.plex.tv/articles/200288926-creating-libraries/]().

## Running
If the config is done properly, a fully functioning mediaserver should only be a `docker-compose up` away.
