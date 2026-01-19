# **Riche Chain Mainnet**

**Riche Chain** is a high-performance, EVM-compatible Layer 1 blockchain built on Hyperledger Besu technology. Utilizing the **QBFT (Quorum Byzantine Fault Tolerance)** consensus mechanism, Riche Chain offers instant finality, high throughput, and enterprise-grade security with low transaction fees.

This repository contains the configuration files required to run a node and connect to the Riche Chain Mainnet.

## **⚡ Network Specifications**

| Parameter | Value | Description |
| :---- | :---- | :---- |
| **Network Name** | Riche Chain Mainnet |  |
| **Chain ID** | 132026 | Hex: 0x203ba |
| **Currency Symbol** | **RIC** | Native Coin |
| **Consensus** | QBFT | Instant Finality (No reorganization) |
| **Block Time** | 3 Seconds | Fast confirmation |
| **Gas Limit** | 25,000,000 | High capacity per block |
| **RPC Endpoint** | https://seed-richechain.com/ | Public RPC |
| **WSS Endpoint** | wss://seed-richechain.com:8586/ | Websocket |
| **Explorer** | [https://richescan.com/](https://richescan.com/) | Block Explorer |

## **📂 Repository Structure**

* genesis.json: The genesis file defining the chain parameters and initial allocations.  
* config.toml: Configuration file for running a Hyperledger Besu node.  
* static-nodes.json: List of stable bootnodes for peer discovery.  
* docker-compose.yml: Docker configuration for quick node deployment.

## **🚀 Getting Started (Run a Node)**

### **Prerequisites**

* **Hardware:** 4 vCPU, 8GB RAM, 100GB+ SSD.  
* **Software:** Docker & Docker Compose **OR** Java JDK 17+ (for binary).

## **🦊 Metamask Integration**

Developers and users can connect to Riche Chain using the following settings in Metamask:

* **Network Name:** Riche Chain Mainnet  
* **RPC URL:** https://seed-richechain.com/  
* **Chain ID:** 132026  
* **Currency Symbol:** RIC  
* **Block Explorer URL:** https://richescan.com/

## **🤝 Contributing**

We welcome contributions from the community. If you find a bug or want to propose an improvement to the node configuration, please open an issue or submit a pull request.

## **📞 Community & Support**

* **Website:** [https://richechain.com](https://richechain.com)  
* **Twitter:** [@richechain](https://x.com/richechain)  
* **Telegram:** [t.me/richechain](https://t.me/richechain)  
* **GitHub:** [github.com/richechain](https://www.google.com/search?q=https://github.com/richechain)

*© 2026 Riche Chain Foundation. All rights reserved.*
