# Disc-NG: Robust Service Discovery in the Ethereum Global Network

Disc-NG is a proposal for service-based peer discovery for the Ethereum Global Network (EGN). 
The EGN hosts a plethora of different sub-networks.
This includes the Ethereum mainnet blockchain, Ethereum testnets but also blockchain-unrelated applications (also called services). 
Once a node joins the EGN it must then locate peer being part of the same service to join the service-specific subnetwork. 
Disc-NG facilitates this process by implementing an efficiency, fair and secure peer discovery protocol. 

The protocol is described in details in our [research paper](https://sonnino.com/papers/disc-ng.pdf) published at [9th IEEE European Symposium on Security and Privacy](https://www.ieee-security.org/TC/EuroSP2024/) . 

## Implementation
* We have the protocol implemented in Java in a PeerSim simulator available [here](https://github.com/datahop/p2p-service-discovery)
* The protocol is also implemented in the devp2p stack used by Geth. This implementation is available [here](https://github.com/datahop/go-ethereum) but it's still under developement and might miss some features. 
