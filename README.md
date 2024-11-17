# nRF Connect SDK docker image

The project was built and tested on MacBook Air M1 MacOS 15

- Build the image:
    ```
    docker buildx build --platform linux/amd64 --no-cache -t ncs .
    ```
- Run the image
    ```
    docker run -it -v ${PWD}:/workdir ncs /bin/bash
    ```