Zetacoin integration/staging tree
=================================

http://www.zeta-coin.org

https://bitcointalk.org/index.php?topic=267545.0

Copyright (c) 2009-2013 Bitcoin Developers

Copyright (c) 2013-2014 Zetacoin Developers

What is Zetacoin?
----------------

Zetacoin is an experimental new digital currency that enables instant payments to
anyone, anywhere in the world. Zetacoin uses peer-to-peer technology to operate
with no central authority: managing transactions and issuing money are carried
out collectively by the network. Zetacoin is also the name of the open source
software which enables the use of this currency.

For more information, as well as an immediately useable, binary version of
the Zetacoin client sofware, see https://bitcointalk.org/index.php?topic=267545.0

License
-------

Zetacoin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.

Vcoin integration
================================

Vcoin specs
----------------

Vcoin sha256 POW!
- 50 coins per block
- static const int64 nTargetTimespan = 1200; 
- static const int64 nTargetSpacing = 30; 
- static const int64 nInterval = nTargetTimespan / nTargetSpacing; // 40 blocks
- 1000000000 total coins


License
-------

Vcoin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.

Development process
-------------------

Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

If it is a simple/trivial/non-controversial change, then one of the vcoin
development team members simply pulls it.

How to compile vcoind on ubuntu 

- git clone https://github.com/vcoindev/vcoin.git
- cd vcoin 


    cd src; make -f makefile.unix 


 for the GUI compile `cd vcoin`. To compile and run them:
 

    qmake "USE_UPNP=-" vcoin-qt.pro
    make -f Makefile
    ./vcoin-qt
    
    Feel free to contritube

- Contact at vcoindev@gmail.com

