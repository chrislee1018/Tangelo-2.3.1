# Tangelo-2.3.1

## Introduction

Tangelo is a single file compressor which was derived from PAQ8 by Matt Mahoney and has been in development since 2013, seeking a balance between compression ratios and speed.

## Purpose

The purpose of this project is to amend memory usage, the state table and state map in Tangelo 2.3 in order to improve the compression achieved.


## Results

This version of Tangelo is benchmarked against the [enwik8 dataset](https://cs.fit.edu/~mmahoney/compression/textdata.html) and, for reference, the dataset is included in this repository.

Version  | Compressed |
| ------------- | ------------- |
| 2.3  | 20921619 bytes  |
| 2.3.1  | 20418854 bytes  |


### Prerequisites

In order to compile Tangelo you need a C++ compiler.


### Installation

Compiling from the command line in Windows using the Microsoft C/C++ Optimizing Compiler:

`cl tangelo.cpp /Ox`

Compiling from the command line in Linux using g++:

`g++ tangelo.cpp -Wall -Wextra -O3 -s -fomit-frame-pointer -o tangelo.exe`

Version  | Compressed |
| ------------- | ------------- |
| 2.3  | 20921619 bytes  |
| 2.3.1  | 20418854 bytes  |
