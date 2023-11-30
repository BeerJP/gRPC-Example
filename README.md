# gRPC-Golang
<br/>
<br/>
<br/>
// Protocol Buffers Compiler <br/>
-- Download <br/>
https://github.com/protocolbuffers/protobuf/releases <br/>
-- Set path to env <br/>
-- Command Prompt <br/>
protoc --version <br/>
-- Terminal FiX <br/>
$env:Path += ";{PATH}" <br/>
<br/>
// Generate Code <br/>
protoc --go_out=. --go-grpc_out=. {PATH}.proto <br/>
