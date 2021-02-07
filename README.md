# prometheus
documentation of prometheus

## integration into golang microservices



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
\> | greater than
\< | lesser than
\>= | greater or equal
\<= | less or equal
=~ | regex equal
!~ | regex not equal

#### logical/set binary operators

work on vectors with matching labels, are similar to joins

binary operator | set theory equivalent | join equivalent
--- | --- | ---
and | intersection | INNER JOIN
or | union | FULL OUTER JOIN
unless | complement | FULL OUTER JOIN WHERE a.key IS NULL OR b.key IS NULL

xxx = variable

rate(xxx[time])
