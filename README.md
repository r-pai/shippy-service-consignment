# shippy-service-consignment

## Genrating protobuf go file from .proto

- Install protoc and proto-gen-go
- From dir /Users/mac/go/src/github.com/r-pai/shippy-service-consignment
   $ protoc -I proto/  proto/consignment/consignment.proto --go_out=plugins=grpc:proto
