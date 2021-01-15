# Enable gpg signed git commits witout entering password

## GnuPG and git setup in a nutshell

Install tools:
~~~shell
brew install gnupg pinentry-mac
~~~

Generate a key and choose 4096 as Key length (minimum):
~~~shell
gpg --full-generate-key
~~~

List your key(s):
~~~shell
gpg --list-secret-keys --keyid-format LONG

sec   rsa4096/XXX
~~~

Create a revokation cert and export keys. Save ~/.gnupg in a save place.
~~~shell
gpg --output ~/.gnupg/revoke.asc --gen-revoke
gpg --export > ~/.gnupg/public_keys.pgp
gpg --export-secret-keys > ~/.gnupg/secret_keys.pgp
~~~

Copy public key to clipboard, then add it to [GitHub settings -> keys](https://github.com/settings/keys)
~~~shell
gpg --armor --export XXX | pbcopy
~~~

Configure git:
~~~shell
git config --global user.signingkey XXX
git config --global commit.gpgsign true
~~~

## Avoid typing in your password

Add '/usr/local/bin/pinentry-mac' in ~/.gnupg/gpg-agent.conf.

Test it:

~~~shell
date > doc
gpg --output doc.sig --sign doc
~~~

That should start Pinentry UI which starts gpg-agent and asks for your password.
Optionally saves your Key password in macOS keychain.
