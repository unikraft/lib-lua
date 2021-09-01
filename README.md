Lua for Unikraft
=============================

This is the port of lua for Unikraft as external library. By default,
when running the port will go into interactive mode. Alternatively,
you can run a script from a file if passed as a initrd parameter.

## Build
Lua depends on the following libraries, that need to be added to `Makefile`:

* `libc`, e.g. [`newlib`](https://github.com/unikraft/lib-newlib)

## Further information

Please refer to the `README.md` as well as the documentation in the `doc/`
subdirectory of the main unikraft repository.
