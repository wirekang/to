# to

A simple packages for golang that provides single function **Do** that can avoids "declared but not used" error.

## Usage

```go
import "github.com/wirekang/to"

to.Do(v1,v2...)

```

## Example

```go
func ExampleFunction () {

  iwill,use := ...();
  this := ...();

  var later Sometype

  to.Do(iwill,use,this,later)
}
```
