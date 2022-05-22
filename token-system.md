## Token System on Kumandra Network  ##

Last Updated 14 May 2022

## 1. Introduction

The Kumandra Network utilises a mathematically complete, peer-to-peer Public Key Infrastructure(PKI) authorisation on an
autonomous network, which mean no human intervention and can't be configure, monitor, and maintain itself independently.
The network is designed to be decentralised and will have the ability to get rid of Domain Name System (DNS). The PKI solution
deployed within the Kumandra network validates a user's identity with mathematical certainty.

## 2. Trusted Group

Kumandra will have a majority of a close group of node that is trustable. While not impossible to generate a majority of malicious
nodes in a close group around a particular target, it should be considered computationally unfeasible.

On Kumandra Network, the following rules ensure a trusted group:

* It is hard to have a miner with a particular address (the address of a new miner will be defined by the network using the hash of the miner’s credentials). In addition, each time a miner is switched off and then rejoins the network, it will be assigned a new address. Furthermore, the node will not be considered a full functional miner until the verification period is complete.

* todo!

## 3. Transfer Mechanism

On Kumandra Network, vaults or miners assume various personas or roles, depending on the requests they receive. For example, the ResourcesManager persona is responsible for managing the integrity and availability of given resources from the miners into the network.
A separate persona, the 'TransactionManager', is proposed to handle all the token-related transactions. A TransactionManager group will be a trusted group of nodes which are closest to any given transaction identity. The TransactionManager is responsible for the logic that enables transactions to be completed.

todo!

## 4. Proof Of Resources

On the Kumandra network, resources providers contribute to the network by running a vault or mining program, which will handle requests and store resources into the network. The following parameters are used to measure a vault and a user account:

* stored_resources: the total size of (CPU Core, Ram, Storage) that have been stored by the miners to the network

* lost_resources: as resources are stored on a node it may switch off or be otherwise unavailable, we consider this to be lost.(Should we?) This is a critically important measure and in no way means the network has actually lost the resources as replicant copies are always available. This is a common practice for a node on the network.

* healthy_resources (h.r.) :  h.r. = stored_resources - lost_resources

* available_resources: the resources availabity to use for a certain tasks. For example, hosting virtual machine, do intense video rendering.

* resources_cost: I don't know maybe rent CPU Core and get free storage and ram?

* used_resources: available_resources - (n) where n is the number of resources used by the clients

