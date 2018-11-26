CLY Coin 0.12.1
=====================

This is the official reference wallet for CLYCoin digital currency and comprises the backbone of the CLYCoin peer-to-peer network. You can [download CLY Coin](https://www.clycoin.org/downloads/) or [build it yourself](#building) using the guides below.

Running
---------------------
The following are some helpful notes on how to run CLYCoin on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/clycoin-qt` (GUI) or
- `bin/clycoind` (headless)

### Windows

Unpack the files into a directory, and then run clycoin-qt.exe.

### OS X

Drag CLYCoin-Qt to your applications folder, and then run CLYCoin-Qt.

### Need Help?

* See the [CLYCoin documentation](https://cly-project.atlassian.net/wiki/display/DOC)
for help and more information.
* Ask for help on [#cly-project](http://webchat.freenode.net?channels=cly-project) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=cly-project).
* Ask for help on the [CLYCoinTalk](https://clycointalk.org/) forums.

Building
---------------------
The following are developer notes on how to build CLY Coin on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The CLY Coin repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- Source Code Documentation ***TODO***
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Unit Tests](unit-tests.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)

### Resources
* Discuss on the [CLYCoinTalk](https://clycointalk.org/) forums, in the Development & Technical Discussion board.
* Discuss on [#cly-project](http://webchat.freenode.net/?channels=cly-project) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=cly-project).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
