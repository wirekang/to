# to

A simple packages for golang that provides single function **Do** that can avoids ```declared but not used``` error.

## Usage

```go
import "github.com/wirekang/to"

to.Do(v1,v2...)

```

## Example

```go
var unusedvar int

to.Do(unusedvar)
```
