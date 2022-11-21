## 步骤
- 执行 protoc -I=./ --go_out-./ ./addressbook.proto
- mkdir -p tutorialpb
- mv github.com/protocolbuffers/protobuf/examples/go/tutorialpb/*.pb.go tutorialpb
- go build ./cmd/add_person/add_person.go
- go build ./cmd/list_people/list_people.go


## TODO
- 什么才是标准化的管理 proto 文件和生产 pb.go 文件的方式呢？这样拷贝太累了吧？
