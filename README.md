# Docker-Stack
Collection of Docker compose yamls

### All folders exist in Documents
For example: /home/user/Documents/esphome

### Other items

Shell script to update container

```sh
#!/bin/bash
docker compose pull
docker compose up --force-recreate --build -d
docker image prune -f
```
