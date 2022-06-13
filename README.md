# gRPC-protofuzz

This package is modified from trailofbits/protofuzz to work with gRPC.  There is no specific installation requirements needed.  See gRPC-fuzzer which uses this repository as a submodule.

# Caveats

Currently, we use [fuzzdb](https://github.com/fuzzdb-project/fuzzdb) for values. This might not be complete or appropriate for your use. Consider swapping it for your own values.
