This library provides Haskell bindings to
[LevelDB](http://leveldb.googlecode.com)

## Installation

Prerequisites:

* [GHC 7.*](http://www.haskell.org/ghc)
* [Cabal](http://www.haskell.org/cabal)
* [LevelDB](https://code.google.com/r/kimaltintop-leveldb)

Note: you'll need to install `libleveldb` as a shared library. The above link
points to a fork of the original LevelDB repo which enables installing LevelDB
as a shared library. To do so, clone the repository and run:

```shell
$ make
$ make install INSTALL_PATH=/usr/local/lib
```

Also, make sure to copy the `include/leveldb` directory to `/usr/local/include`.

Then, install `leveldb-haskell` from source:

```shell
$ cabal install
```

## Notes

This library is in very early stage and has seen very limited testing. Comments
and contributions are welcome.

## Bugs and Contributing

Please report issues via http://github.com/kim/leveldb-haskell/issues.<br />
Patches are best submitted as pull requests, or via email
(kim.altintop@gmail.com).

## License

BSD 3, see LICENSE file.
