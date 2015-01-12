Barrelfish's Mackerel
=====================

Mackerel is a domain-specific language used to describe hardware devices
and the in-memory formats of registers and data structures like
descriptor lists, page-table entries, etc.

This repository contains the unmodified and unsupported source that is part
of the [Barrelfish Operation System](http://www.barrelfish.org).

This tool is written in Haskell and depends on Parsec.
Build and explore the example as follows:

    cabal build
    ./dist/build/mackerel/mackerel -c examples/fat32_ebpb.dev -o include/fat32_ebpb.h

For more documentation, check out the
[Mackerel User Guide](http://www.barrelfish.org/TN-002-Mackerel.pdf)
