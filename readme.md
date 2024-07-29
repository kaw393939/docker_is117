Docker Commands

1. See my QR demo of docker for commands: [here](https://github.com/kaw393939/improved-qr-docker-2024)

2. My docker command was docker commit

``` sh
docker commit [OPTIONS] CONTAINER [REPOSITORY[:TAG]]
```

3. Another docker command is docker exec. Here is how you use it:

``` sh
docker exec [OPTIONS] CONTAINER COMMAND [ARG...]
```

Here is an example of when it might be used:

``` sh
docker exec -it my_container /bin/bash
```

This opens a bash shell inside of a running container

4. Another docker command is docker run. Here is how you use it:

``` sh
docker run [OPTIONS] IMAGE [COMMAND] [ARG...]
```

Here is an example of when it might be used:

``` sh
docker run ubuntu echo "Hello, Docker!"
```

This will create and run a new container from the ubuntu image and execute the echo "Hello, Docker!" command.

5. Another docker command is docker commit. Here is how you use it:

``` sh
docker commit [OPTIONS] CONTAINER [REPOSITORY[:TAG]]
```

Here is an example of when it might be used:

``` sh
docker commit my_container my_image
```

This will create an image called my_image from the current state of my_container.


