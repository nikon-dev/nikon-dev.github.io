---
{
    .title = "Matrix Multiplication Optimisation",
    .date = @date("2024-08-28T00:00:00"),
    .author = "Nikon Sugar",
    .draft = false,
    .layout = "page.shtml",
    .tags = ["AI", "news"],
}  
--- 

Matrix muliplication (matmul) is a fundamental operation in machine learning. It is often the bottle-neck of model training and inference performance. This note is to review some recent techniques to optimise matmul efficiency.


*This is a sample code of matrix multiplication in Zig*

```zig
const std = @import("std");
const log = std.log.scoped("matmul");

log.info("Here is the matmul optimisation to be upated.", .{});
```

*Here is a sample in Go language*

```go
package main

import(
    "fmt"
)

func main(){
    fmt.Println("Here is matmul to be updated...")
}
```


