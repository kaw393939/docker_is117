Docker Commands

1. See my QR demo of docker for commands: [here](https://github.com/kaw393939/improved-qr-docker-2024)






- Docker `exec` Commands
The `docker exec` command allows you to run commands in a running container. Here are some common use cases and examples:
```sh
docker exec [OPTIONS] CONTAINER COMMAND [ARG...]
```
##Running a one-off command to list files in the /app directory inside the container.
```
docker exec my_app_container ls /app
```
