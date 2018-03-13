[![Build status](https://api.travis-ci.org/plotify/releases.svg?branch=master)](https://travis-ci.org/plotify/releases)

```batch
$ gpg --list-secret-keys
$ gpg -u KEY_ID --textmode --output latest.json.sig --detach-sig latest.json
$ gpg --no-default-keyring --keyring ./public_keys/releases.gpg --verify latest.json.sig latest.json
```
