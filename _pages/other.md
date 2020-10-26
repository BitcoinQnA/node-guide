---
layout: page
title: Other Options
permalink: /other/
---

There are plenty of options when it comes to running your own node. The previous pages cover the most popular and user friendly routes. The options that follow are geared more towards advanced users who may require a custom configuration to serve a specific purpose. 

#### Samourai Dojo

[Samourai Dojo](https://code.samourai.io/dojo/samourai-dojo) is the backing server for Samourai Wallet. Provides HD account & loose addresses (BIP47) balances & transactions lists. Provides unspent output lists to the wallet. PushTX endpoint broadcasts transactions through the backing bitcoind node. Dojo comes packaged with some of the software covered elsewhere on this website but this [installation guide](https://github.com/Samourai-Wallet/samourai-dojo/blob/master/doc/DOCKER_setup.md) is for the standalone setup on Linux.

#### Ubuntu Node Box (Virtual Machine)

[Ubuntu Node Box](https://www.youtube.com/watch?v=BIrL1lNsnJQ&list=PLCRbH-IWlcW17JxQ4mdv9DwSMJZlvUOle&index=1) is a video guide by Ketan of [Ministry of Nodes](https://www.ministryofnodes.com.au/). In this series, Ketan covers setting up a node in an Ubuntu virtual machine to download and install Bitcoin Core, Electrum Server, Lightning, BTCPay Server, JoinMarket, Whirlpool and much more.

#### Nix Bitcoin

[Nix Bitcoin](https://github.com/fort-nix/nix-bitcoin) packages and nixos modules for easily installing Bitcoin nodes and higher layer protocols with an emphasis on security. This is a work in progress - don't expect it to be bug-free, secure or stable. The default configuration sets up a Bitcoin Core node and c-lightning.

#### Cyphernode

[Cyphernode](https://github.com/SatoshiPortal/cyphernode) is designed to be deployed on virtual machines with launch scripts, but with efficiency and minimalism in mind so that it can also run on multiple Rasberry Pi with very low computing ressources (and extremely low if installing pre-synchronized blockchain and pruned). Because of the modular architecture, heavier modules like blockchain indexers are optional (and not needed for most commercial use-cases).

