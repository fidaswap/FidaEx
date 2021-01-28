# The FIDA Ledger

The FIDA Ledger is a decentralized cryptographic ledger powered by a network of peer-to-peer servers. The FIDA Ledger uses a novel Byzantine Fault Tolerant consensus algorithm to settle and record transactions in a secure distributed database without a central operator.

## FIDA
FIDA is a public, counterparty-less asset native to the FIDA Ledger, and is designed to bridge the many different currencies in use worldwide. FIDA is traded on the open-market and is available for anyone to access. The FIDA Ledger was created in 2021 with a finite supply of 1.2 billion units of FIDA. FIDA uses FIDA the help build the Internet of Value, ushering in a world in which money moves as fast and efficiently as information does today.

## file
The server software that powers the FIDA Ledger is called `file` and is available in this repository under the permissive [ISC open-source license](LICENSE). The `file` server is written primarily in C++ and runs on a variety of platforms.

### Build from Source

* [Linux](Builds/linux/README.md)
* [Mac](Builds/macos/README.md)
* [Windows](Builds/VisualStudio2017/README.md)


### Repository Contents

| Folder     | Contents                                         |
|:-----------|:-------------------------------------------------|
| `./bin`    | Scripts and data files for Ripple integrators.   |
| `./Builds` | Platform-specific guides for building `file`. |
| `./docs`   | Source documentation files and doxygen config.   |
| `./cfg`    | Example configuration files.                     |
| `./src`    | Source code.                                     |

Some of the directories under `src` are external repositories included using
git-subtree. See those directories' README files for more details.

