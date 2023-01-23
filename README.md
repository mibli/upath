### Micro (µ) Path (upath)

Compresses path mainly for prompt use, addressing the problem of ugly wrapping, or lengthy prompts.
I don't think it has much use outside of it, but feel free to let me know if You do. It should be
compatible with paths with spaces and Unicode.

Example of usage (see -h for more):

    $ pwd | upath                     # compress path
    ~/r/upath
    $ echo "/u/b/bash" | upath -x     # expand path
    /usr/bin/bash

Possible future features:

* removal of existence requirement for shortening (would need to implement a few tweaks)
* vowel removal
* preserving the trailing 's' (indicating multiple)
* tests
