# wazo-keyring

wazo-keyring is a Debian package that manages GnuPG archive keys used by Wazo Platform.

To work with wazo-keyring.gpg, always use a gpg command starting with:

```
gpg --keyring ./wazo-keyring.gpg --no-default-keyring ...
```

For example, updating the GPG key:

```
gpg --keyring ./wazo-keyring.gpg --no-default-keyring --import wazo-platform.key
```
