# Simple DAXPY with MKL in Swift

More details for installing MKL see https://github.com/chiroptical/swift-mkl

I will assume the directory you installed MKL is `/home/chiroptical/src/mkl`

To build,

```
swift build -Xcc -I/home/chiroptical/src/intel/mkl/include -Xlinker -L/home/chiroptical/src/intel/mkl/lib/intel64
```

To run,

```
swift run -Xcc -I/home/chiroptical/src/intel/mkl/include -Xlinker -L/home/chiroptical/src/intel/mkl/lib/intel64
```
