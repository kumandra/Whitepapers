## Blockchain-based Decentralized Storage Scheme

`Abstract`. There are many possible way to achieve decentralized storage solution but what this paper trying to achieve is not only DSN(Decentralized Storage Network) but value of the whole ecosystem. This paper proposes a decentralized storage system based on blockchain technology, and also IPFS which can make full use of
the remaining space of personal hard disks of the users all around the world and a fair decentralized storage network for the storage providers. Storage provider will be decoupled into storage pool. End-user that want to use the platform will pay and the storage fee will given to the pool that
actually store the data from the uploader. In order to provide a fair solution to all storage provider, there is a solution that the system will randomly choose any pool or we can say it is _load-balanced_. All proofs and payment information are stored in the blockchain, which guarantees the
security and credibility of the system.

### 1. Introduction

Over the past few years, with the continuous improvement of information technology, the demand for computing and resource storage has grown rapidly. People continuously exploring new ways of computing and seek of higher computing power and larger storage capacity.
Cloud computing distributes computing tasks across resource pools of a large numbers of computers, enabling applications systems to acquire more computing power, storage, space, and storges as a service needed.
    
Cloud storage systems enable users to access massive 
amounts of storage at a cheaper price but come with a price. User store their data only in one place and they don't have full control over their data. Most of the cloud storage companies, currently still provide their own centralized storage space, and do not meet the requirements for storage
resource integration and distributed storage.

This paper proposes a distributed storage scheme based on blockchain. The user uploads the data, and the system will randomly choose one cluster pool in the system as storage holder for the user. The user uses Kumandra Network Token to pay the storage fee to the cluster pool address. The reward
will be locked until it reach the certain block in Kumandra Network. If user decided to store data on the network for 1 month, when the block reach the 1 month timestamp. The cluster pool will get their storage fee reward and the user data will be unpinned until the network storage garbage
collection run. In those period, if the user decided to continue pinning, they need to revoke the pinning certificate and continue the payment.
