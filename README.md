# 4chan-dl

A script to download media from 4chan threads. Previously downloaded threads are saved to a log file. Use `4chan-update` to download new media.

## Compatibility

Linux

## About

This script might not be the fastest way to download 4chan threads, but it suits my needs as it allows users to specify unique output directories for each thread.

## Installation

1. Place `4chan` and `4chan-update` in your `.local/bin` folder.
2. Call them from the command line.

## Usage

### Downloading Threads

To download a thread, use the following command:

```bash
4chan -o "/output/directory" "thread_url"
