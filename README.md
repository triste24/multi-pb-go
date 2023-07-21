# multi-pb-go
Here's a Go code example with support for multiple Protobuf files, where A.pb depends on B.pb.

```
 protoc -I=./proto --go_out=./ --go_opt=paths=source_relative ./proto/**/*.proto
```
