# Контракт для Auth сервиса

## Для генерации protobuf файлов нужно выполнить следующую команду (появятся в директории gen/go/sso)

```
protoc -I proto proto/sso/sso.proto --go_out=./gen/go --go_opt=paths=source_relative --go-grpc_out=./gen/go/ --go-grpc_opt=paths=source_relative
```
