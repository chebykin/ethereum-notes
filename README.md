# Ethereum Notes

## Web Services
* https://github.com/cubedro/eth-netstats (https://hub.docker.com/r/buythewhale/ethstats/)

## TestRPC
* TestRPC is a wrapper around ganacha-core.
* ganacha's team working on visual version of their server with electron.js interface (Oct 9, 2017)

### Commands
* testrpc -m <12 word metamask password that gives when downloading metamask>

### Bugs
* Fails to work with WS (Oct 9, 2017)

## Web3.js
* v1.x.x doesn't support synchronous calls like v0.x.x, so it's uncompatible with TestRPC https://github.com/trufflesuite/ganache-core/pull/14 (Oct 9, 2017)

### Bugs
* v0.x.x contract creation callback can be triggered 2 times: after transaction creation and after transaction verified. But can not.
