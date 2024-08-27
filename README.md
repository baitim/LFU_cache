<h1 align="center">LFU cache</h1>

## Description

 Implementation of the LFU(least frequently used) cache and a comparison with the Belady's cache.

## How to run

1. Clone <br>
    write <code>git clone https://github.com/baitim/LFU_cache.git</code> in terminal

2. Go to folder <br>
    write <code>cd LFU_cache</code> in terminal

3. Build <br>
    write <code>cmake . -B build & cmake --build build</code> in terminal

4. Run <br>
    for LFU:    write <code>./build/lfu/lfu</code> in terminal
    for Belady: write <code>./build/belady/belady</code> in terminal

## How to test

1. Go to folder <br>
    write <code>cd tests</code> in terminal

2. Generate tests <br>
    write <code>python3 generate.py</code> in terminal

3. Run testing <br>
    write <code>./run_tests.sh</code> in terminal

The test result will be in the "answer.dat" file

<p align="center"><img src="https://github.com/baitim/LFU_cache/blob/main/images/cat.gif" width="40%"></p>

## Support
**This project is created by [baitim](https://t.me/bai_tim)**
