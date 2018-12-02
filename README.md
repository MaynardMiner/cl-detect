# cl-detect

Used to detect OpenCL platform indexes

List OpenCL platforms and devices:

$ clang -framework OpenCL platforms.c -o platforms && ./platforms
$ clang -framework OpenCL devices.c -o devices && ./devices

clang devices.c -o devices -lOpenCL
clang platforms.c -o platforms -lOpenCL
