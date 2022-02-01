# Project 2 Docker Implementation

Build Docker Container
```
docker build --rm . -t p2
```

Run Docker Container and Build Project
```
docker run --rm -ti -v "$(pwd)":/home p2
make
```