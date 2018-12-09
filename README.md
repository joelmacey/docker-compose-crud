# Simple Node.js CRUD with MongoDB using Docker Compose

## Requirements

* [Docker](https://www.docker.com/products/docker-desktop) at Version 17.03.2-ce or above (This is the version used during development).

* [Docker Compose](https://docs.docker.com/compose/install/) at Version 1.23.1 or above (This is the version used during development).

## Starting your containers

Run this in the current directory
```
docker-compose up
```

In order to rebuild your app on starting your containers run
```
docker-compose up --build
```

## Sample Data

I have included a JSON file with 8 sample books to be displayed when the containers start.
This file was obtained [here](https://gist.github.com/nanotaboada/6396437).
