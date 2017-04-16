# Dawn network

> Pushing down costs while pushing up quality and giving access to money that cannot be debased.

<span class="Pushing down the deep state while pushing up humanity"></span>

 D.istributed A.utonomous W.orldwide N.etwork

 > A multiple linked blockchain based platform for everything people do with IT devices.

 The down network is a set of tools containing multiple hardwares such as routers and softwares such as blockchain nodes and client applications.

## Abstract

Blockchain technology has enjoyed an exponential rise in awareness. It offers a unique distributed data set, leading to ultra-high speed transactions and a new level of security via ultra-secure access and the consensus of distributed validation protocols. All this is delivered at a far reduced cost per transaction.

DAWN also offers an extraordinary group of blockchain and traditional protocol specialists. This Development Group comprises on-line architects to generate solutions to your functionality requirements. Your business can now enjoy the future of Digital Communications.

DAWN services:

 * Encrypted, hashed, secure, fast, low-cost file storage and Finer Retrieval of Digital Assets.
 * Blazing fast real-time execution, logging and data update of transactions.
 * Provide a messaging/video/docs sharing system for the most time-efficient interconnectivity of an entire company.
 * Start your own blockchain-generated currency.
 * Tailor-made incentivized, blockchain-based rewarding social media platform.
 * Diverse Digital Asset Store with Multi-Protocol Access Permissions.
 * Streamline the distribution of Market Sensitive Intellectual Property Assets – Media, Listed Company Reports, Confidential Client Data, Data Rooms for Due Diligence Requirements are some examples.
 * Finer Real Time Inventory Control Management.

Beyond Expectations.

DAWN advantages comparing to existing similar services provider.

 * Faster.
 * Cheaper.
 * More secure, immutable over non-owner.

Respecting privacy, liberty, equality.

Pushing forward technology.

## Table of contents

* [Abstract](#abstract)
* [Table of Contents](#table-of-contents)
* [Design](#design)
  * [Dawn OS](#dawn-os)
  * [Dawn hardwares](#dawn-hardwares)
    * [Dawn R1](#dawn-r1)
    * [Dawn R2](#dawn-r2)
    * [Dawn OP1](#dawn-op1)
  * [Network schema](#network-schema)
  * [Blockchains](#blockchains)
    * [Exchange chain](#exchange-chain)
    * [Glog chain](#glog-chain)
    * [ID chain](#id-chain)
    * [JSON chain / File chain](#json-chain-/-file-chain)
 * [Client applications](#client-applications)
   * [Dawn client](#dawn-client)
   * [Dawn light client](#dawn-light-client)
 * [Library](#library)
   * [Dawn JS](#dawn-js)
     * [EGIJF JS](#egif-js)
       * [EC JS](EC-js)
       * [GC JS](GC-js)
       * [IC JS](IC-js)
       * [JC JS](JC-js)
       * [FC JS](FC-js)


## Introduction

Let's upgrade the web.

## Design

### Dawn OS

Desktop OS including all the stuff needed to run Dawn network related stuff.

 * [Packer](https://www.packer.io/)
 * [Arch Linux](https://www.archlinux.org/)
 * [Wire Guard](https://www.wireguard.io/)
 * [Zero Tier](https://www.zerotier.com/) ?
 * [Glog chain](#glog-chain) *
 * [ID chain](#id-chain) *
 * [File chain / JSON chain](#file-chain-/-json-chain) *
 * [Dawn client](#dawn-client) *

`* Optional`

### Dawn hardwares

#### Dawn R1

* 4 Cores 2.4GHz+
  * Intel atom Z3740 / AMD A8-7600
* 4GB RAM (Up to 8GB)
* 64GB SSD
* 802.11ac x2 MIMO
* Dawn OS

Designed for a low cost Glog chain master node and client.

Costs: ~ 300$ to 400$.

#### Dawn R2

* 4 Cores 2.4GHz+
  * Intel atom Z3740 / AMD A8-7600
* 4GB RAM (Up to 8GB)
* 64GB SSD + 4To HDD
* 802.11ac x2 MIMO
* Dawn OS

Designed for a low cost File chain node and client.

Costs: ~ 350$ to 450$.

![](https://github.com/dawn-network/white-paper/blob/master/images/Dawn_R1.png?raw=true)

#### Dawn OP1

* [Orange PI PC](http://www.orangepi.org/orangepipc/) with 8GB memory.
* Dawn OS

Designed for a low cost Dawn client.

Costs: ~ 20$ to 35$.

### Network schema

![Dawn diagram 0.1](https://github.com/dawn-network/white-paper/blob/master/images/Dawn_diagram.png?raw=true)

### Blockchains

name_code: undefined

#### Exchange exchange

name_code: cypher

Blockchain offering a stack of financial services including exchange and banking.

This will be used correlates blockchain accounts value.

Work similarly as [bitshares](https://bitshares.org/).

#### Glog chain

name_code: morpheus

Cryptocurrency enabled blockchain content distribution and compensation platform.

Contain a set of posts and accounts.

 * A post contain small meta-data and a list of entries of File-chain type.
 * A post can be public or private (avaible with a key).
 * A post have a value (`pw`) in function of `vote(-100% to +100%), user_reputation, eyeball_time ?`, algorithm must still be optimized, the user must be logged to be counted and have a limited self-regenerating interaction bar `?`.
 * A post split it's value into 1+ accounts, this split occurs every X Days.
 * An account have a value and a list of transactions only visible for the account holder.

![pv/pw](https://github.com/dawn-network/white-paper/blob/master/images/curve.png?raw=true)

90% of the amount goes into content creators, 10% into entries validators.

The reward pool distribution curve of the first Glog chain over posts `pw`.

Work similarly as [Steem](https://steem.io).

#### ID chain

name_code: trinity

Blockchain that correlates blockchain addresses to enable cross-chain flows.

Work similarly as [ethereum](https://www.ethereum.org/)

#### JSON chain / File chain

name_code: the_oracle

Cryptocurrency enabled blockchain managing ifps links, debiting/crediting accounts. Providing a ultra-secure, highly-encrypted + hashed, and 99.99999% avaible decentralized and off-chain file and data storage.

JSON chain work similarly as File chain except that files are stored in RAM and limited in size.

Work similarly as [Filecoin](http://filecoin.io/)/[Storj](https://storj.io/).

### Client applications

Client use [WebTorrent](https://webtorrent.io/)/[WebRTC](https://webrtc.org/) part of [libp2p](https://github.com/libp2p/libp2p) to seed recent files they have viewed and for P2P communication. Providing a real-time scalable bandwith capacity.

Client interact with all blockchains.

#### Dawn client

name_code: red_pill

Interact with all blockchains, is part of the JSON / File chain for by default the file size needed by the account.

#### Dawn light client

name_code: blue_pill

Interact with all blockchains, is not part of the JSON / File chain.

## Library

### Dawn JS

JavaScript library for an easy implementation of the dawn network across web application including tools.

#### EGIJF JS

JavaScript library for an easy implementation of the dawn blockchains across web application.

#### EC JS

JavaScript library for an easy implementation of the Exchange chain across web application.

#### GC JS

JavaScript library for an easy implementation of the Glog chain across web application.

#### IC JS

JavaScript library for an easy implementation of the ID chain across web application.

#### JC JS

JavaScript library for an easy implementation of the JSON chain across web application.

#### FC JS

JavaScript library for an easy implementation of the File chain across web application.
