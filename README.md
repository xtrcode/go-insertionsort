# Straightforward, in-place <strong>Insertion sort</strong> implementation in Go
## Usage
```go
sorted := Sort([]int{3,8,4,9,6,5,1,7,0,2,8})
fmt.Println(sorted)
```

## Benchmark
Hardware: Xeon E3-1231 v3/32GB | 
OS: Ubuntu 18.04
<pre>
goos: linux
goarch: amd64
BenchmarkSort10-8               2000000000               0.00 ns/op
BenchmarkSort100-8              2000000000               0.00 ns/op
BenchmarkSort1000-8             2000000000               0.00 ns/op
BenchmarkSort10000-8            2000000000               0.02 ns/op
BenchmarkSort100000-8                  1        3429396276 ns/op
PASS
ok      go/src/insertionsort    3.683s

</pre>
Expected run-time: O(n^2)

# LICENSE
This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

In jurisdictions that recognize copyright laws, the author or authors
of this software dedicate any and all copyright interest in the
software to the public domain. We make this dedication for the benefit
of the public at large and to the detriment of our heirs and
successors. We intend this dedication to be an overt act of
relinquishment in perpetuity of all present and future rights to this
software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to <http://unlicense.org/>