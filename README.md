# Mediapi
A 2D and 3D API

## Prerequisites
Create an .env file in the project directory and add your custom values to build the image and run a container.

Example:

```bash
USER=mkuegeler
PROJECT=mediapi
REPO="$USER/$PROJECT:latest"
IMAGE="$PROJECT-image"
CONTAINER="$PROJECT-container"
HOST="localhost"
INTERNAL_PORT="80"
EXTERNAL_PORT="8080"

```

## Build and run

```bash

bash ./app.sh

```
