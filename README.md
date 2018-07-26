## Docker 101
This is a challenge repository! You must:

1. Containerize a Python application using [alpine](https://hub.docker.com/r/library/alpine/) as base image.
2. Dockerfile must be as modular as possible.
3. Add library dependencies using a `requirements.txt` external file.
4. Add application code to your docker image by copying a `src\` folder.
5. Customize `entrypoint.sh` (notice difference between `RUN` and `CMD`).
6. Mount a volume to store results locally so that data is persisted.
7. Have fun ;-)

### Suggested repository structure:
```
├───Dockerfile
├───requirements.txt
└───src
    ├───app.py
    └───entrypoint.sh
```

### Useful resources:
Official documentation 101: https://docs.docker.com/v17.03/get-started/ 
Docker-hub for inspiration and base images: https://hub.docker.com
