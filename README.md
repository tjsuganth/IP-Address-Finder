# IP Address Finder

A simple C project that demonstrates how a splay tree can be used to store and retrieve IP address entries with associated data packet values.

## Overview

This repository contains a small educational implementation of a splay tree in C. Each node stores:

- an IP address value
- a data packet value
- left, right, and parent pointers

The program inserts several IP values, assigns random packet data to them, performs searches, and prints the final tree contents in sorted order.

## Files

- `Splay Tree.c` - the complete implementation of the splay tree and sample demo program

## How it works

The program:

1. creates a new splay tree
2. inserts multiple IP values
3. searches for specific entries
4. stores random packet values for each match
5. traverses the tree in-order and prints the result

## Build and Run

Compile the program with GCC:

```bash
gcc "Splay Tree.c" -o ipfinder
./ipfinder
```

## Example Output

```text
IP ADDRESS -> DATA PACKET
192.168.3.104 -> 87
192.168.3.108 -> 42
192.168.3.109 -> 63
...
```

## Notes

- The IP values are represented as integer suffixes, such as `104`, `109`, and `129`, with the prefix `192.168.3.` added in the output.
- This project is intended for learning and demonstration of splay tree operations in C.
- It is not a production-ready networking or IP scanning utility.
