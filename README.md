Simple version generation tool
================================


#### Usage:
```bash
go get dev.hexasoftware.com/hxs/genversion
# generate a file containing Version variable fetched from git tags
genversion -package main -out version.go
```

#### Sample output:
genversion -package main -out version.go    
file version.go
```go
package main

const (
  //Version contains version of the package
  Version = "0.1 - built: 2017-07-10 16:14:22 UTC"
)
```



#### Requires:   
*	git
