# Go Modules 
- hello 
- greetings

`Hello` calls `Greetings`

### Run
```
cd hello
go run .
```

### Commands
```
go mod init example.com/greetings
go mod init example.com/hello
go mod edit -replace=example.com/greetings=../greetings
go mod tidy
```