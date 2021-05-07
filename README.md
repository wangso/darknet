# This is a modified version of the original darknet repo from: [Darknet](https://github.com/pjreddie/darknet)

### In this version, I have 

1. Updated Makefile to enable GPU with nVidia V100 version

2. Modified the Makefile, src/image.c, src/image.h, python/darknet.py to include ndarray library, which increases the performance of GPU based image object classification.

3. Compiled libdarknet.so to allow using nVidia V100 GPU and ndarray. 

### This repo can be downloaded directly to be used for V100 GPUs and ndarray libary, or recompile with appropriate settings for other GPUs. 

