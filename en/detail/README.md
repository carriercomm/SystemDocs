# Libraries

The SAFE network is comprised of several individual libraries. The following section, aimed at the more technical reader, provides a more detailed explanation of what role each library performs and how they work.The following diagram provides an overview of the SAFE Network stack and how all the components fit together:



The code for each library is available in MaidSafe's [GitHub repository](https://github.com/maidsafe). The libraries are:

1.  Crust- Reliable p2p network connections in Rust with NAT traversal
2.  Routing - A secured DHT, based on a kademlia-like implementation, that has group based consensus decisions confirmed by Sentinel
3.  Vault - An autonomous network that perform many functions including data storage, data management, publishing and sharing that receives responsibilities for anything with a network address from the routing layer
5.  Encrypt - Self-encrypting files (convergent encryption plus obfuscation)
6.  Drive - A virtual drive offering services to store and retrieve information to any storage media including network file systems



