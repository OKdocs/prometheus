# prometheus
documentation of prometheus


## kinds of data to collect

### counter

exists also as vector
```go
implementation
```
when to use

### histogram

exists also as vector, but please don't use
```go 
implementation
```

when to use

### gauge

## analysis

### operators

#### arithmetic binary operators

same as always, `+`, `-`,`*`,`/`,`%`,`^` as known from literaly all programming languages

#### comparison operators

operator | meaning
--- | ---
== | equal
!= | not equal
> | greater than
< | lesser than
>= | greater or equal
<= | less or equal
=~ | regex equal
!~ | regex not equal

xxx = variable

rate(xxx[time])
