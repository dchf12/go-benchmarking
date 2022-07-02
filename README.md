# go-benchmarking
Benchmarks are the most straightforward way to check the performance of code

## run the benchmark 
```
goos: windows
goarch: amd64
pkg: github.com/dchf12/benchmarking
cpu: Intel(R) Core(TM) i7-6700HQ CPU @ 2.60GHz
BenchmarkInsertionSort/input_size_10-8         	62500976	        17.04 ns/op	       0 B/op	       0 allocs/op
BenchmarkInsertionSort/input_size_100-8        	 6042231	       172.6 ns/op	       0 B/op	       0 allocs/op
BenchmarkInsertionSort/input_size_1000-8       	  713133	      1562 ns/op	       0 B/op	       0 allocs/op
BenchmarkInsertionSort/input_size_10000-8      	   70484	     15631 ns/op	       0 B/op	       0 allocs/op
BenchmarkInsertionSort/input_size_100000-8     	       1	2516483400 ns/op	       0 B/op	       0 allocs/op
BenchmarkMergeSort/input_size_10-8             	 9648194	       120.4 ns/op	       0 B/op	       0 allocs/op
BenchmarkMergeSort/input_size_100-8            	  705856	      1707 ns/op	       0 B/op	       0 allocs/op
BenchmarkMergeSort/input_size_1000-8           	   60615	     21847 ns/op	       0 B/op	       0 allocs/op
BenchmarkMergeSort/input_size_10000-8          	    4069	    283616 ns/op	       0 B/op	       0 allocs/op
BenchmarkMergeSort/input_size_100000-8         	     412	   3137433 ns/op	       0 B/op	       0 allocs/op
PASS
coverage: 88.2% of statements
ok  	github.com/dchf12/benchmarking	16.016s
```
