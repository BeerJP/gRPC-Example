# gRPC-Golang
<br/>
<br/>
<br/>
// Install package <br/>
go get -u google.golang.org/grpc <br/>
go get -u github.com/golang/protobuf/protoc-gen-go <br/>
// Protocol Buffers Compiler <br/>
-- Download <br/>
https://github.com/protocolbuffers/protobuf/releases <br/>
-- Set path to env <br/>
-- Command Prompt <br/>
protoc --version <br/>
-- Terminal Fix <br/>
$env:Path += ";{PATH}" <br/>
<br/>
// Generate Code <br/>
protoc --go_out=. --go-grpc_out=. {PATH}.proto <br/>
