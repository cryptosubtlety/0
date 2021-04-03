A few _more_ 0-related fixed bugs I found last year that I haven't included in the paper:

1/ 0-length signature or 0-length message, supranational/blst: crashed https://github.com/supranational/blst/commit/64a22698fcfae9845c07c5030adadaab4a258dd3

2/ inverse(0) mod p = 0, but inverse(p) mod p = 1: https://github.com/ethereum/py_ecc/pull/114
