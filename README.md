# Rewind - A termux backup/restore tool


Simple bash script to backup and
restore home directory and packages installed manually.

![rewind](rewind.png)

## Installation

Just copy paste this in your termux.

1.

```bash
apt-get update && apt-get upgrade -y
```

2.

```bash
apt-get install curl tar -y
```

3.

```bash
curl -O https://raw.githubusercontent.com/DethByte64/TermuxBackupTools/master/rewind && chmod u+x rewind && mv rewind $PREFIX/bin/
```

## Usage

Usage : **rewind**  [-hvu] [-b|-r [home|pkgs]]

option           |   Description
:---------------:|:---------------------------:
 -h              |    print this usage
 -v              |    print version
 -u              |    update the script
 -b [home|pkgs]  |    backup home and/or packages
 -r [home|pkgs]  |    restore home and/or packages

