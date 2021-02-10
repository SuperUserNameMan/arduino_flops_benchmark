# arduino_flops_benchmark
Arduino FLOPS benchmark based on "Linpack Floating Point benchmark"

original port from : https://gist.github.com/projectgus/8279947

I was wondering how an Arduino Nano or MiniEVB Nano would compare to the Top500 supercomputers ... 

| optimization level | LGT8F328p @ 32MHz | LGT8F328p @ 16MHz | ATmega328p |
|:-:|:-:|:-:|:-:|
| Os | 205 kFLOPS |||
| O0 | 160 kFLOPS |||
| O1 | 204 kFLOPS |||
| O2 | 205 kFLOPS |||
| O3 | 220 kFLOPS | 109kFLOPS | 90 kFLOPS |
| Ofast | 226 kFLOPS | 112kFLOPS | 92 kFLOPS |
