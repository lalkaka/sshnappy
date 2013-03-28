sshnappy
========

sshnappy is an effort to retrofit the snappy compression library onto OpenSSH.
OpenSSH currently supports zlib for over-the-wire compression.
However, enabling zlib compression on a modern internet connection typically lowers effective link throughput -- zlib is too computationally intensive to be useful at accelerating ssh connections on high bandwidth links.

Snappy is designed from the ground up for use cases like this.
