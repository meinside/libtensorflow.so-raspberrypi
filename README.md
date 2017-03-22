# libtensorflow.so for Raspberry Pi

This repository is for storing pre-built **libtensorflow.so** files.

Read [this post](https://blog.meinside.pe.kr/TensorFlow-and-Go-on-Raspberry-Pi/) if you want to build one yourself.

## How to use

Download the .tgz file from [here](https://github.com/meinside/libtensorflow.so-raspberrypi/releases).

Unzip it and move it into `/usr/local/lib`.

```bash
$ tar -xzvf libtensorflow_v0.0.0_2999-12-31.tgz
$ sudo mv libtensorflow.so /usr/local/lib/
$ sudo ldconfig
```
