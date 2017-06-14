grpc-builder
============

A docker image to generate code for gRPC

Build the image:

```
docker build -t grpc-builder .
```

Use it on a folder with .proto files:

```
docker run -v `pwd`/proto:/proto grpc-builder
```
