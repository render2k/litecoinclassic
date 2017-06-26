Litecoin Classic (LTCC)
===========

Scrypt Hashcash PoW

===========

Binary Wallets:

Linux: TO DO
Deb package: TO DO
Windows installer: TO DO

Build dependencies:

libboost (C++ libraries)
libdb (Berkeley DB 4.8, dev)
Qt 4.8.7 + Qt Creator
libssl (dev)
git (optional)
libminiupnpc (dev)
ZMQ (dev)
libqrencode (dev)

Quick guide for building Qt-based wallet in Ubuntu 16.04+ 64-bit:

1. sudo apt-get install build-essential libtool autotools-dev automake pkg-config libssl-dev libevent-dev bsdmainutils
2. sudo apt-get install libboost-system-dev libboost-filesystem-dev libboost-chrono-dev libboost-program-options-dev libboost-test-dev libboost-thread-dev
3. sudo apt-get install software-properties-common
4. sudo add-apt-repository ppa:bitcoin/bitcoin
5 . sudo apt-get update
6 . sudo apt-get install libdb4.8-dev libdb4.8++-dev
7. sudo apt-get install libminiupnpc-dev
8. sudo apt-get install libzmq3-dev
9. sudo apt-get install libqrencode-dev
10. sudo apt-get install qt4-dev-tools
11. sudo apt-get install qtcreator
12. run qtcreator, open the ".pro" file, configure the project, uncheck the shadow build, press CTRL+B.