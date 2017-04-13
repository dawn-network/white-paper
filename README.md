# Dawn network

Pushing down costs while pushing up quality and giving access to money that cannot be debased.

<span class="Pushing down the deep state while pushing up humanity"></span>

## Abstract

The down network is a set of tools containing multiple hardwares such as routers and softwares such as blockchain nodes and client applications.

## Table of contents

* [Abstract](#abstract)
* [Table of Contents](#table-of-contents)
* [Design](#design)
  * [Dawn OS](#dawn-os)
  * [Dawn hardwares](#dawn-hardwares)
    * [Dawn R1](#dawn-r1)
    * [Dawn OP1](#dawn-r1)
  * [Network schema](#network-schema)
  * [Blockchains](#blockchains)
    * [Glog chain](#glog-chain)
    * [ID chain](#id-chain)
    * [File chain / JSON chain](#file-chain-/-json-chain)
 * [Client applications](#client-applications)
   * [Dawn client](#dawn-client)
   * [Dawn light client](#dawn-light-client)


## Introduction

Let's upgrade the web.

## Design

### Dawn OS

Desktop OS including all the stuff needed to work Dawn network stuff.

 * [Packer](https://www.packer.io/)
 * [Arch Linux](https://www.archlinux.org/)
 * [Wire Guard](https://www.wireguard.io/)
 * [Zero Tier](https://www.zerotier.com/) ?
 * [Glog chain](#glog-chain)
 * [ID chain](#id-chain)
 * [File chain / JSON chain](#file-chain-/-json-chain)   
 * [Dawn client](#dawn-client)

### Dawn hardwares

#### Dawn R1

Coming soon.

#### Dawn OP1

[Orange PI PC](http://www.orangepi.org/orangepipc/) with 8GB memory.

### Network schema

![Dawn diagram 0.1](https://github.com/dawn-network/white-paper/blob/master/images/Dawn_diagram.svg?raw=true)

### Blockchains

name_code: undefined

#### Glog chain

name_code: morpheus

Cryptocurrency enabled blockchain content distribution and compensation platform.

Contain a set of posts and accounts.

 * A post contain small meta-data and a list of entries of File-chain type.
 * A post can be public or private (avaible with a key).
 * A post has a value (`pv`) in function of `[((user_reputation / 2) x eyeball_time) x view_number]) ?`, the user must be logged to be counted and have a limited self-regenerating interaction bar `?`.
 * A post split it's value into 1+ accounts, this split occurs every X Days.
 * An account have a value and a list of transactions only visible for the account holder.

90% of the amount goes into content creators, 10% into entries validators.

The reward pool distribution curve of the first Glog chain over posts `pv` is at `2/3` linear and `1/3` exponential.

Work similarly as [Steem](https://steem.io).

#### ID chain

name_code: trinity

Blockchain that correlates blockchain addresses to enable cross-chain flows.

#### JSON chain / File chain

name_code: the_oracle

Cryptocurrency enabled blockchain managing ifps links, debiting/crediting accounts. Providing a ultra-secure, highly-encrypted + hashed, and 99.99999% avaible file and data storage.

Work similarly as [Filecoin](http://filecoin.io/)/[Storj](https://storj.io/).

### Clients applications

Client use [WebTorrent](https://webtorrent.io/)/[WebRTC](https://webrtc.org/) part of [libp2p](https://github.com/libp2p/libp2p) to seed recent files they have viewed and for P2P communication. Providing a real-time scalable bandwith and.

Client interact with all blockchains.

#### Dawn client

name_code: red_pill

Interact with blockchains, is part of the JSON / File chain.

#### Dawn light client

name_code: blue_pill

Interact with blockchains, is not part of the JSON / File chain.
