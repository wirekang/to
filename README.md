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

for easy debuging

![image](https://user-images.githubusercontent.com/43294688/139572539-8702009c-b909-441a-9b63-76cf6ae0f13e.png)
