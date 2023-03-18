# example-proto

Provide proto for goravel/example

```shell
# 1. Install Protocol Buffers
#    https://github.com/protocolbuffers/protobuf/releases
# 2. Install protoc-gen-gofast
#    go install github.com/gogo/protobuf/protoc-gen-gofast
protoc --gofast_out=plugins=grpc:. *.proto
```
