[![OS Version](https://img.shields.io/badge/OS-ubuntu%2016.04-blue.svg)](https://shields.io/)
[![cuda](https://img.shields.io/badge/cuda-9.0-orange.svg)](https://developer.nvidia.com/cuda-90-download-archive) 
[![cudnn](https://img.shields.io/badge/cudnn-7.5-orange.svg)](https://developer.nvidia.com/rdp/cudnn-download)
[![lmdb](https://img.shields.io/badge/lmdb-ON-brightgreen.svg)](https://github.com/LMDB/lmdb)
[![leveldb](https://img.shields.io/badge/leveldb-OFF-lightgray.svg)](https://github.com/google/leveldb/tree/v1.20)
[![hdf5](https://img.shields.io/badge/hdf5-OFF-lightgray.svg)](https://github.com/UMKC-CPG/olcao/wiki/HDF5-Installation-Guide)
[![Build Status](https://travis-ci.org/BVLC/caffe.svg?branch=master)](https://travis-ci.org/BVLC/caffe) [![make](https://img.shields.io/badge/make-passing-brightgreen.svg)](https://github.com/LMDB/lmdb) [![cmake](https://img.shields.io/badge/cmake-untest-lightgray.svg)](https://nvidia.com)
[![License](https://img.shields.io/badge/license-BSD-blue.svg)](LICENSE)

# Caffe

## Dependencies

* protobuf 3.5.0 ([install](https://github.com/protocolbuffers/protobuf/releases/tag/v3.5.0))
* glog 0.3.3
* gflags
* lmdb ([install](https://github.com/LMDB/lmdb))
* ~~leveldb 1.20 ([install](https://github.com/google/leveldb/tree/v1.20))~~
* cuda 9.0
* cudnn 7.5


## Installation

1. modify `Makefile.config`
2. `make clean && make pycaffe`

