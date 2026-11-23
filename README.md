# LZW Compression ALgorithm
Simple implementation of Lempel-Ziv-Welch file compression in C++.

## How it works
The algoritm builds a dictionary of common character chunks, then encodes the text using that dictionary along with a key. The file is then decompressed using the stored key.

## Usage
Place the file to be compressed in your working directory. Run compress.cpp and input the file name. To decompress your file, run decompress.cpp and input the file name once again.
