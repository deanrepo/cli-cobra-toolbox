### a small program of golang cobra cli

### Docs
[cobra github](https://github.com/spf13/cobra)
[cobra viper github](https://github.com/spf13/viper)

### Install cobra
```
    $ go install github.com/spf13/cobra-cli@latest
```

### add a new command
```
    $ cobra-cli add [COMMAND NAME]
```

### How to use
```
    $ go run main.go net -h
    $ go run main.go net ping -u [URL]

    $ go run main.go info -h
    $ go run main.go info diskUsage
```