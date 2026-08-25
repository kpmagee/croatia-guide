# croatia-guide

An encrypted, single-file travel guide. `index.html` is an AES-256-GCM
ciphertext with a PBKDF2-SHA256 (600,000 iteration) password gate in front of
it — there is no readable content in this repository. Without the passphrase
there is nothing here to read.

Rebuilt from a private source repo; do not edit `index.html` by hand.
