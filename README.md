# Etherem Notes

## TestRPC
* TestRPC is a wrapper around ganacha-core.
* ganacha's team working on visual version of their server with electron.js interface (Oct 9, 2017)

### Commands
* testrpc -m <12 word metamask password that gives when downloading metamask>

### Bugs
* Fails to work with WS (Oct 9, 2017)

## Web3.js
* v1.x.x doesn't support synchronous calls like v0.x.x, so it's uncompatible with TestRPC https://github.com/trufflesuite/ganache-core/pull/14 (Oct 9, 2017)
