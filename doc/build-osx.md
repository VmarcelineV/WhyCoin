Build instructions
===================

See readme-qt.rst for instructions on building WhyCoin QT, the
graphical user interface.

All of the commands should be executed in Terminal.app

```
sudo port install boost db48 openssl miniupnpc qrencode

cd whycoin/src
make -f makefile.osx
```

```
./whycoind --help  # for a list of command-line options.

./whycoind -daemon # to start the whycoin daemon.

./whycoind help # When the daemon is running, to get a list of RPC commands
```
