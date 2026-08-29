# benchmarks
[![Hugo Version](https://img.shields.io/badge/dynamic/yaml?url=https%3A%2F%2Fraw.githubusercontent.com%2Fjackrschumacher%2Fdevices%2Fmain%2Fdevices%2F.hvm&query=%24&label=hugo&color=FF4088&logo=hugo)](https://github.com/jackrschumacher/benchmarks)

## Running benchmarks

### sbc-bench

```shell
# Run the script and write to a file while also displaying on screen
sudo /bin/bash ./sbc-bench.sh -r | tee benchmark_results.txt
```

### Geekbench 6
On Linux:
```shell
wget https://cdn.geekbench.com/Geekbench-7.0.0-Linux.tar.gz
tar -xzvf Geekbench-7.0.0-Linux.tar.gz
cd Geekbench-7.0.0-Linux
./geekbench7 #Run just the CPU benchmark
./geekbench7 --cpu #Specifically run just the CPU benchmark
./geekbench7 --compute #Run GPU benchmark
./geekbench7 --compute-list #Check available compute APIs
./geekbench7 --compute OpenCL #Run OpenCL
./geekbench7 --compute Vulkan #Run Vulkan
```