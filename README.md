# monero-wallet-generator-d6
Monero offline wallet generator, dice (d6) version

This page generates a new Monero address. It is self contained and does all the necessary calculations locally, so is suitable for generating a new wallet on a machine that is not connected to the network, and may even never be. This way, you can create a Monero wallet without risking the keys.

This is a fork of the original one, which replaces custom entropy with dice rolls. The idea is to use them directly as the seed, ie, just roll a big enough base6 number and convert to base16 for seed.

- Work in progress -
