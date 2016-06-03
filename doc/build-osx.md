Build instructions
===================

See readme-qt.rst for instructions on building DBGold QT, the
graphical user interface.

All of the commands should be executed in Terminal.app

```
sudo port install boost db48 openssl miniupnpc qrencode

cd dbgold/src
make -f makefile.osx
```

```
./dbgoldd --help  # for a list of command-line options.

./dbgoldd -daemon # to start the dbgold daemon.

./dbgoldd help # When the daemon is running, to get a list of RPC commands
```
