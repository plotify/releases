[![Build status](https://api.travis-ci.org/plotify/releases.svg?branch=master)](https://travis-ci.org/plotify/releases)

```batch
$ gpg --textmode --armor --output latest.json.asc.txt --detach-sig latest.json
$ gpg --no-default-keyring --keyring ./public_keys/releases.gpg --verify latest.json.asc.txt latest.json
```
