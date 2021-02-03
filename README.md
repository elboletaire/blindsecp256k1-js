# blindsecp256k1-js [![npm](https://img.shields.io/npm/v/blindsecp256k1)](https://img.shields.io/npm/v/blindsecp256k1)

Javascript implementation compatible with https://github.com/arnaucube/go-blindsecp256k1

Blind signature over [secp256k1](https://en.bitcoin.it/wiki/Secp256k1), based on *"[New Blind Signature Schemes Based on the (Elliptic Curve) Discrete Logarithm Problem](https://sci-hub.do/10.1109/ICCKE.2013.6682844)"* paper by Hamid Mala & Nafiseh Nezhadansari.

**WARNING**: this repo is experimental, do not use in production.

## Build for browser
By running `npm run browserify`, and the file `blindsecp256k1-browser.js` will be generated, which can be imported in the html and used as `blindsecp256k1`.
