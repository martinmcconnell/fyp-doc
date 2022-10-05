---
title: "Adapting to Censorship in a Centralised Internet"
titlepage: true
titlepage-background: "background1.pdf"
page-background: "background1.pdf"
author: [Martin McConnell - 20088021]
date: "01-01-2023"
keywords: [break stuff]
listings-no-page-break: true
listings-disable-line-numbers: true
code-block-font-size: \scriptsize
toc-own-page: true
list-of-figures: true

...

# Abstract
An analysis of censorship prevalence, it's uses and misues from a socio-political point of view
and demonstrating alternative technologies to help end-users be more self reliant on open source
software and try to improve on the technical barrier between new technologies and them. The core
of the project will revolve around utilising technologies such as IPFS to create an open source
file-sharing client possibly using the bittorrent style protocol most likely devloped in Golang
using go-ipfs and orbitdb. This client may also incorporate a bulletin board type system (BBS)
for idea sharing amongst clients including a small amount of multi-user-dungeon style gaming.
As a possible aside the repository may also be hosted on IPFS using radicle.xyz.
For a database i would also like to incorporate GUN.js backend mobile app for accessing services
securely with encryption this would also host a chat app with a novel design.

# Introduction

## Purpose
## Intended use and Audience
## Goals and Requirements
### Goals
### Requirements


# Methodology
The first half of this section is research and an exploration of tech,
leading to the developmental approach to be taken i.e. Agile, TDD etc.

## Decentralised

### peer 2 peer

### Beaker Browser
#### dat protocol
#### Hyperdrive

### gun.js
#### end-to-end encryption
#### Distributed Hash Tables

## Blockchain
### What is a blockchain
###
## Comparing technologies (IPFS, Zeronet, LBRY, BitTorrent)


## Development cycle?
### An Agile Approach with Kanban
Using Trello, Sprints

### Test-Driven-Development
### Continuous Integration/Development
Build – We will compile the code in this stage.

Test – We will test the code in this stage. We can save both efforts as well as
time can be saved by performing the techniques of automation.

Release – In this stage, we will release the application in our GitHub repository.

Deployment – We will deploy the application to the production environment.

Validation and compliance – Your organization’s needs determine the steps to validate a build.
### Golang on IPFS

### Installing and operating radicle [ To be removed ]
On Debian/Ubuntu the package manager must be altered by first entering the signing key, then update the
sources.list file, finally updating and installing via apt.

```sh
$ curl https://europe-west6-apt.pkg.dev/doc/repo-signing-key.gpg | sudo apt-key add -
$ echo deb https://europe-west6-apt.pkg.dev/projects/radicle-services radicle-cli main | sudo tee -a /etc/apt/sources.list.d/radicle-registry.list
$ sudo apt update
$ sudo apt install radicle-cli

```
# Results

# Discussion

# Conclusion

# References

# Bibliography

- Benet, J.. (

- Paul Eve, M. (2021) WAREZ, The Infrastructure and Aesthetics of Piracy. Earth, Milky Way, Punctum Books.

- infourminutes.co (2018) IPFS Whitepaper in Four Minutes. Available at: https://medium.com/coinmonks/ipfs-whitepaper-in-four-minutes-b3d5eb0e75c6 (Accessed: 19 September 2022)

- LBRY (2019) Available at: https://lbry.com/faq/different-ipfs (Accessed: 21 September 2022)

- Ernesto Van der sar (2019) Decentralized 'Pirate Bay' with IPFS. Available at: https://torrentfreak.com/torrent-paradise-creates-decentralized-pirate-bay-with-ipfs-190120/ (Acessed: 26 September 2022)

- Ignacia Larrain (2022) Will Google Analytics be Banned in Europe? Not as easy as it seems. Available at: https://visionarymarketing.com/en/2022/04/google-analytics-ban/ (Accessed: 26 September 2022)

- Nisha Jain (2022) EU declares Google Analytics illegal: Here’s why. Available at: https://techstory.in/eu-declares-google-analytics-illegal-heres-why/ (Accessed: 26 September 2022)


