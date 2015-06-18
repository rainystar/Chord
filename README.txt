INSTRUCTIONS
------------

[Language]
 - Python 2.7


[Environment]
 - Ubuntu 14.04

[Dependency]
 - Communication: Thrift 0.9.2

[Preparation]
1. Thrift
    download stable release thrift-0.9.2.tar.gz from https://thrift.apache.org/download
    $ sudo apt-get install libboost-dev libboost-test-dev libboost-program-options-dev libboost-system-dev libboost-filesystem-dev libevent-dev automake libtool flex bison pkg-config g++ libssl-dev
    $ sudo apt-get install default-jdk (or other jdk packages)
    $ sudo apt-get install python-all python-all-dev python-all-dbg
    $ cd thrift-0.9.2
    $ ./configure
    $ make
    $ make check
    $ sudo make install
