generate:
	protoc -I.:/usr/local/include --gofast_out=../../../../.. google/api/annotations.proto
	protoc -I.:/usr/local/include --gofast_out=../../../../.. google/api/http.proto
	protoc -I.:/usr/local/include --gofast_out=../../../../.. google/rpc/code/code.proto
	protoc -I.:/usr/local/include --gofast_out=../../../../.. google/rpc/errdetails/error_details.proto
	protoc -I.:/usr/local/include --gofast_out=../../../../.. google/rpc/status/status.proto

clean:
	find . -regex "\.\/.*\/.*\.go" -exec rm {} +