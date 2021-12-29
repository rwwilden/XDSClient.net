A GRPC client for the Envoy XDS API.

### Submodule
The required proto files need to be included as a Git submodule:

    git submodule init
    git submodule update


### Add protobuf references

     dotnet-grpc add-file -s Client ../data-plane-api/envoy/api/v2/cds.proto -i ../data-plane-api