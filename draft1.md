## Blockchain-based Decentralized Storage Scheme

`Abstract`. 
There are many possible ways to a decentralized storage solution. Though the existing solutions are not yet mature and can offer anything superior to the current centralized cloud storage. In this paper, we present a Decentralized Storage Network (DSN) based on blockchain technology and IPFS. The system could provide ways to utilize the remaining spaces of personal hard disks and empower users around the world to take part of the network. In turn, receive reward for sharing these resources. Storage providers could decouple into a storage pool. End-users pay the storage and network fees. The storage fees will be distributed to the pools that actually store the data. In order to provide a fair solution to storage providers, the system will randomly choose a pool and monitor the liveness of the whole network. All proofs and payment information are stored on-chain, which guarantees security and credibility of services and value of the system.

### 1. Introduction

Over the past few years, with the continuous improvement of information technology, the demand for computing and resource storage has grown rapidly. People continuously exploring new ways of computing and seek of higher computing power and larger storage capacity.
Cloud computing distributes computing tasks across resource pools of a large numbers of computers, enabling applications systems to acquire more computing power, storage, space, and storges as a service needed.
    
Cloud storage systems enable users to access massive 
amounts of storage at a cheaper price but come with a price. User store their data only in one place and they don't have full control over their data. Most of the cloud storage companies, currently still provide their own centralized storage space, and do not meet the requirements for storage
resource integration and distributed storage.

This paper proposes a distributed storage scheme based on blockchain. The user uploads the data, and the system will randomly choose one cluster pool in the system as storage holder for the user. The user uses Kumandra Network Token to pay the storage fee to the cluster pool address. The reward
will be locked until it reach the certain block in Kumandra Network. If user decided to store data on the network for 1 month, when the block reach the 1 month timestamp. The cluster pool will get their storage fee reward and the user data will be unpinned until the network storage garbage
collection run. In those period, if the user decided to continue pinning, they need to revoke the pinning certificate and continue the payment.

### 2. Implementing Mechanism and Principle

The design of Kumandra Protocol is trying to be simple and simplicity, anyone with spair storage capacity and want to rent it out for some reward and help the network to grow. Kumandra combines a set of technologies such as IPFS, IPFS-Cluster and Substrate to build a decentralized storage platform on top of a P2P
network.

### 2.1. Overview: Kumandra Barrel

Barrel is a tool used for registering as storage worker and pledging unused storage to the network.

### 2.2. Blockchain: Storage Worker
