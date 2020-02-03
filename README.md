# shippy-service-consignment

## Generating protobuf go file from .proto

- Install protoc and proto-gen-go
- From dir github.com/r-pai/shippy-service-consignment
   $ protoc -I proto/  proto/consignment/consignment.proto --go_out=plugins=grpc:proto

## Reference
https://ewanvalentine.io/microservices-in-golang-part-1/
