# 12-words

Quickly generate a cryptographically secure twelve word mnemonic to be used as a passphrase or key.

```
> docker run namick/12-words
desk grow warm depend aspect moment turkey zebra lend glove install jar
```

## Description

Uses a [javascript](https://github.com/bitpay/bitcore-mnemonic) implementation of [Bip39](https://github.com/bitcoin/bips/blob/master/bip-0039.mediawiki) to create a mnemonic code to be used for generating a passphrase or deterministic keys.
