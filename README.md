Exmy integration/staging tree
================================

https://elly.com

Copyright (c) 2009-2019 Bitcoin Developers
Copyright (c) 2011-2019 Litecoin Developers
Copyright (c) 2019 Exmy Developers

What is Exmy?
----------------

Exmy is a cryptocurrency that is intended for internal use in the EXLLY exchange platform. This cryptocurrency is used among other things for the payment of fees and payment on the e-commerce website of Exlly.

Name : Exmy

Ticker : EXMY

Block Time : 10 seconds

Retarget Time : 30 seconds

Build on UNIX
-------

    sudo add-apt-repository ppa:bitcoin/bitcoin -y && apt-get update -y
    sudo apt-get install build-essential libtool libminiupnpc-dev autotools-dev -y
    sudo apt-get install libssl1.0-dev autoconf libdb4.8-dev libdb4.8++-dev libboost-all-dev -y
    git clone https://github.com/EXLLY/exmy.git
    cd exmy/src
    make -f makefile.unix


License
-------

Exmy is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.
