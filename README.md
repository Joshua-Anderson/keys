### Joshua Andeson's Public Keys

This is where I store my public pgp and ssh keys.

I'll also update this folder to contain revocations and such over time.

#### PGP Keys

- Primary key: [j@joshua-anderson.com `5FFE0FA1`](https://raw.githubusercontent.com/Joshua-Anderson/keys/master/5FFE0FA1.pgp)

I also publish my keys to the ubuntu keyserver, so they can be added to your keychain with
`gpg --keyserver keyserver.ubuntu.com --recv-key <key id>`

#### SSH Keys

- Primary key: [j@joshua-anderson.com `FB31D05B`](https://raw.githubusercontent.com/Joshua-Anderson/keys/master/FB31D05B.pub)

#### Checking for tampering:

Every file in this repository is signed. Make sure the keys haven't been tampered with!
Verify their signature with `gpg --verify <filename>.sig <filename>`

Every git commit is also signed for additional security.
