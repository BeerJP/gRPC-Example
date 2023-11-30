# gRPC-Example
<br/>
<br/>
<br/>
// Protocol Buffers Compiler <br/>
1) Download <br/>
- https://github.com/protocolbuffers/protobuf/releases <br/>
2) Set path to env <br/>
3) Command Prompt <br/>
- protoc --version <br/>
4) Terminal Fix <br/>
- $env:Path += ";{PATH}" <br/>
5) Generate Code <br/>
- protoc --go_out=. --go-grpc_out=. {PATH}.proto <br/>
<br/>
<br/>
// Golang Install package <br/>
go get -u google.golang.org/grpc <br/>
go get -u github.com/golang/protobuf/protoc-gen-go <br/>
