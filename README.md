# Create and Run the Docker Image `ubuntu-robust`

Open the terminal and navigate to the directory where the `Dockerfile` is already created. Run the following commands to build the image and run the container:

## Build image
```bash
docker build -t ubuntu-robust .
```

## Run Container
```bash
docker run -it --name ubuntu-robust ubuntu-robust bash
```
