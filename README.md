# logit

This is a simple logging helper for Golang.


## Setup

It takes an environment variable called LOG_LEVEL.

Valid options are: DEBUG|INFO|WARN|ERROR|FATAL
Default is: INFO

## Usage

```
logit.Debug("some debug message")
logit.Info("%s file not found", filename)
logit.Warn("some warn message")
logit.Error("some error message")
logit.Fatal("some fatal message")
```