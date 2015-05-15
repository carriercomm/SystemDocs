## Routing Overview

A secured DHT, based on a kademlia-like implementation, but with some very stark differences. This is a recursive as opposed to iterative network, enabling easier NAT traversal and providing more efficient use of routers and larger networks. This also allows very fast reconfiguration of network changes, aleviating the requirement for a refresh algorithm. A recursive solution based on a network protocol layer that is 'connection oriented' also allows a close group to be aligned with security protocols.

This library makes use of Public-key cryptography to allow a mechanism to ensure nodes are well recognised and cryptographically secured. This pattern allows the creation of a DHT based PKI and this in turn allows a decentralised network to make use of groups as fixed in relation to any address. This is particularly useful in a continually fluid network as described here, creating a server-less and autonomous network.

This is a very under researched area. For a general introduction to some of the ideas behind the design related to XOR Space, watching The SAFE Network from First Principles series is recommended. The slides for XOR Distance Metric and Basic Routing lecture are also available here. The last video from the series on how the same ideas were applied to decentralised BitTorrent trackers is available here. A proper formalisation of the Routing algorithm is in progress.

Pre-requisite:

libsodium is a native dependency for sodiumxoide. Thus, install sodium by following the instructions here.

For windows, download and use the prebuilt mingw library. Extract and place the libsodium.a file in "bin\x86_64-pc-windows-gnu" for 64bit System, or "bin\i686-pc-windows-gnu" for a 32bit system.

