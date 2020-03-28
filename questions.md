# Questions

## What's `stdint.h`?

A header file in the standard C library.

## What's the point of using `uint8_t`, `uint32_t`, `int32_t`, and `uint16_t` in a program?

These provide us with data types to make our code simpler to read and more efficient.

## How many bytes is a `BYTE`, a `DWORD`, a `LONG`, and a `WORD`, respectively?

1, 4, 8, 2

## What (in ASCII, decimal, or hexadecimal) must the first two bytes of any BMP file be? Leading bytes used to identify file formats (with high probability) are generally called "magic numbers."

BM in ASCII, 0x42 0x4D in Hexadecimal

## What's the difference between `bfSize` and `biSize`?

bfSize is the total file size and includes the header. biSize does not include the header

## What does it mean if `biHeight` is negative?

The image is stored top to bottom.

## What field in `BITMAPINFOHEADER` specifies the BMP's color depth (i.e., bits per pixel)?

WORD biBitCount;

## Why might `fopen` return `NULL` in `copy.c`?

The file does not exist or cannot be opened.

## Why is the third argument to `fread` always `1` in our code?

We are attempting to read individual bytes.

## What value does `copy.c` assign to `padding` if `bi.biWidth` is `3`?

3

## What does `fseek` do?

It changes the location of file position by a set amount.

## What is `SEEK_CUR`?

Selects the location to ofset from (when using fseek) to the current location.
