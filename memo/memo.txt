
go get google.golang.org/grpc

protoc --go_out=./ --go-grpc_out=./ proto/*.proto

go install google.golang.org/protobuf/cmd/protoc-gen-go@latest
go install google.golang.org/grpc/cmd/protoc-gen-go-grpc@latest
