# soft-ieee754

This is a software implementation of the ieee754 floating point format for any
size with any configuration for exponent, mantissa and bias values, allowing you
to create any size floating point format when unavailable by the hardware.

Notable examples are 'half-precision' floating points (also known as binary16)
used in graphic processing hardware not available on modern CPUs, or needed for
compact network transmission of floating points.

## Why?

Most hardware today only supports 32bit (single precision) and 64bit (double 
precision) floating points in hardware, without support for other sizes that are
useful when compactness is needed.

## Status

Currently the library is in a WIP state. 
