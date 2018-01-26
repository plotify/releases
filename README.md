```batch
$ gpg --output latest.json.sig --detach-sig latest.json
$ gpg --no-default-keyring --keyring ./public_keys/releases.gpg --verify latest.json.sig latest.json
```
