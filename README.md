#Curecoin Client
###Client for the CureCoin cryptocurrency

### New to CureCoin?

If you are a newcomer, check out this [this website](http://curecoin.net/) which explains Curecoin in simple and everyday terms. You can find statistics on the current state of the Curecoin network [on this page](http://stats.curecoinfolding.com/).

Joining the Curecoin network is easy:

1. Install the [Folding@home software] (http://folding.stanford.edu/)
2. Pick a username & get a [passkey] (http://folding.stanford.edu/home/faq/faq-passkey/)
3. Enter "224497" as the team number to fold under
4. Register on [cryptobullionpools.com] (https://www.cryptobullionpools.com/) with the **exact** same username 
5. Expect your coins within 24 hours!

### System requirements

1. The Linux operating system.

### Installation

There are two CureCoin clients that you can choose: one with a nice graphical interface, and one that operates entirely in the command-line. The first is highly recommended and is a good choice for most users, but expert users may prefer the command-line (headless) client instead. The GUI client is known as "curecoin-qt" and the headless client is called "curecoind". Installing either one or both is extremely simple. Just follow these directions:

* **Install from source**

  This involves downloading the source, meeting the dependencies, compiling the code, and then installing the resulting software. 

   git clone https://github.com/cygnusxi/CurecoinSource.git

    FOR THE GUI CLIENT:

    > 1. **sudo apt-get --no-install-recommends install qt4-qmake libqt4-dev libboost-dev libboost-system-dev libboost-filesystem-dev libboost-program-options-dev libboost-thread-dev libssl-dev libminiupnpc-dev libdb5.1++-dev dh-make build-essential**
    > 2. From the main directory, run the following:
    > 3. **qmake && make**
    > 4. **sudo make install** Alternatively, don't run that command and just place the binary wherever you want.

    FOR THE HEADLESS CURECOIND:

    > 1. **sudo apt-get --no-install-recommends install libboost-all-dev libqrencode-dev libssl-dev libdb5.1-dev libdb5.1++-dev libminiupnpc-dev dh-make build-essential**
    > 2. **cd src/ && mkdir obj/ && make -f makefile.unix**
    > 4. **sudo make install** Alternatively, don't run that command and just place the binary wherever you want.

    libdb4.8 should also work if libdb5.1 is too high a version for you. Newer versions of Linux will need libdb5.3++-dev

### Reporting bugs or getting assistance

General help for CureCoin can be found on the forums at https://www.curecoin.net/forum or on #curecoin in irc.freenode. The forum is recommended for non frequent users of irc. 

### Donations

Stars on this repo are appreciated as it helps improve the visibility of this repository. If you'd like to do more than that, tip cryptocurrency to:


CygnusXI - CureCoin Dev

CureCoin wallet B4nMZWxPs7mjUacHYf5wmtEEd489UpnExd

Bitcoin wallet: 1G1Sac4sJXqTu2ZhPJFH86HVqs6YKFD4MW
