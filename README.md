## This is the offical Trapcoin Github.

Trapcoin is based on CryptoNote and uses the CryptoNight algorithm.

There is a max supply of 100.000.000 coins and the blocktime is 120 seconds.

We also have a discord server if you have questions or want to support the project:
https://discord.gg/fEkvN39

## Building:

### On *nix:

Dependencies: GCC 4.7.3 or later, CMake 2.8.6 or later, and Boost 1.55.

You may download them from:

* http://gcc.gnu.org/
* http://www.cmake.org/
* http://www.boost.org/
* Alternatively, it may be possible to install them using a package manager.

To build, change to a directory where this file is located, and run `make`. The resulting executables can be found in `build/release/src`.

### On Windows:
Dependencies: MS Visual Studio Community 2013 or later, Python 2.7, CMake 2.8.6 or later, and Boost 1.55. You may download them from:

You can also look here: https://github.com/trapcoin-dev/Trapcoin/blob/master/windows-requirements-install.md

* http://www.microsoft.com/
* https://www.python.org/
* http://www.cmake.org/
* http://www.boost.org/

To build, change to a directory where this file is located, and run these commands: 
```
mkdir build
cd build
cmake -G "Visual Studio 12 Win64" ..
```

For a GUI look here: https://github.com/trapcoin-dev/Trapcoin_gui

## Mining:

Start ```trapcoind```

Then you can use ```miner``` to start mining.

Config options can be viewed with ```miner --help```

You can also mine with ```simplewallet```:

Open your wallet from there and then start with ```start_mining X (number of threads)```

You should also be able to use any CryptoNight GPU miner, use ```127.0.0.1:8340``` as address.

## Donations:

BTC: 1LzpxtVRXMrLxGckC1PfsZA8o6TssLmocY

ETH: 0x70EAE40Be33aC8f59f24C52a0443F7EBe3e168B8

XMR: 46NQEMcGSYk1AeHjSRrxtMD5Zy1bqrB4gFpqBjWD8rEg5aXFKMz9VzN3rq6RH55hGJSsfWh9zQvEzDPefwYndFEw4CAYQ5H

TRAPS:


### This project is NOT associated with https://coinmarketcap.com/currencies/trapcoin/
