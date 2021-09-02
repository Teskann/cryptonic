# Cryptonic

Easily encrypt and decrypt files / folders in Linux !

### :warning: Disclaimer :warning:

This is not a serious project. See this as a cloud backup of two bash files.

## Requirements

 - [gpg](https://gnupg.org/) :lock:
 - [tar](https://www.gnu.org/software/tar/) :file_folder:
 - [python](https://www.python.org/downloads/) :snake:

## Installation

```
git clone git@github.com:Teskann/cryptonic.git
cd cryptonic
chmod +x encrypt
chmod +x decrypt
cp encrypt decrypt ~/bin/
cd ..
rm -rf cryptonic
```

## Usage

```
encrypt FILE_OR_DIR
```

```
decrypt FILE
```