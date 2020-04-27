Safecrex Core 1.0.0
=================

This is the official reference wallet for Safecrex digital currency and comprises the backbone of the Safecrex peer-to-peer network. You can [download Safecrex Core](https://github.com/safecrex-official/safecrex/releases) or [build it yourself](#building) using the guides below.

Running
---------------------
The following are some helpful notes on how to run Safecrex on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/safecrex-qt` (GUI) or
- `bin/safecrexd` (headless)

### Windows

Unpack the files into a directory, and then run safecrex-qt.exe.

### OS X

Drag Safecrex-Qt to your applications folder, and then run Safecrex-Qt.

### Need Help?

* See the [Safecrex documentation](https://safecrexpay.atlassian.net/wiki/display/DOC)
for help and more information.
* Ask for help on [#safecrexpay](http://webchat.freenode.net?channels=safecrexpay) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=safecrexpay).
* Ask for help on the [SafecrexTalk](https://safecrextalk.org/) forums.

Building
---------------------
The following are developer notes on how to build Safecrex Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Safecrex Core repo's [root README](/README.md) contains relevant information on the development process and automated testing.

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
* Discuss on the [SafecrexTalk](https://safecrextalk.org/) forums, in the Development & Technical Discussion board.
* Discuss on [#safecrexpay](http://webchat.freenode.net/?channels=safecrexpay) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=safecrexpay).

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
