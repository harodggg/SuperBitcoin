# A Value Internet Sharing Bitcoin’s Consensus Security

## Abstract
Super Bitcoin is a value-based internet centered around BTC, and sharing Bitcoin's consensus security. 
This value internet not only inherits the security of the existing Bitcoin network but also transcends BTC's current limitations of being solely used for transfer, providing the Bitcoin network with unlimited scalability and flexibility.

Although the Lightning Network [2] inherits Bitcoin's network security and offers partial scalability solutions, it still falls short in supporting smart contracts and further enhancing scalability.
We propose a five-layer architecture for Super Bitcoin using the Bitcoin network as the kernel layer, maintaining system security and transaction irreversibility through the proof-of-work (PoW) consensus mechanism; building an efficient communication layer based on the Lightning Network, facilitating rapid transmission of asset information while preserving Bitcoin's decentralized nature;
we introduce the Taproot Consensus as the extension layer, abstracting Lightning Network communication and asset information to provide a standardized interface for the upper virtual machine layer;
a multi-chain layer, also known as the fusion layer, consists of multiple lightning chains secured by BTC consensus, integrating any mainstream virtual machine (VM) to achieve a "Multi-chain interconnection“ and ”multi-chain interoperability” unified by BTC consensus;
finally, at the application layer, providing developers with rich tools and interfaces to build a decentralized application (DApp) ecosystem, all sharing the security of BTC consensus.

## 1. Introduction
As the pioneer of cryptocurrencies, Bitcoin (BTC), through its proof-of-work (PoW) consensus mechanism and decentralized network structure, has garnered an immense level of consensus, becoming a supranational currency. This security stems from the perfect combination of its vast network hash power and economic incentives.
The birth of Bitcoin not only ushered in a new era of decentralized digital currency but also pointed the way for the subsequent development of blockchain technology. 
However, the limitations of Bitcoin’s scripting language soon became apparent, as it only supports simple value transfers and limited contract logic, unable to meet the demands of more complex decentralized applications.

The evolution of blockchain technology is essentially all about expanding and enhancing Bitcoin's capabilities.
Vitalik Buterin, the founder of Ethereum, initially envisioned adding smart contract functionality to Bitcoin. 
However, due to the technological constraints of the time and the limitations of the Bitcoin network, Ethereum had to establish its own independent consensus system. 
While this approach allowed for the creation of Turing-complete smart contracts, it also introduced new security risks and scalability challenges. 
Many projects followed suit, building independent blockchain ecosystems, gradually diverging from and even forgetting the original intention of extending Bitcoin’s capabilities.

However, two key factors remind us of the need to reconsider this direction. 
First, the continued rise in Bitcoin’s value relative to other cryptocurrencies like Ethereum has validated the trust people place in its security and stability. 
Second, the collapse of Luna/UST, which wiped out nearly $100 billion in market value, highlighted the severe security vulnerabilities present in independent consensus chains, especially when faced with complex economic models and rapidly growing network value.
In this context, we introduce Super Bitcoin to create a true value internet sharing Bitcoin's consensus security.
It fundamentally differs from the existing Bitcoin Layer 2 solutions: traditional Bitcoin Layer 2 solutions (such as the Lightning Network) mainly achieve fast payments through off-chain state channels and limited scripts, while sharing Bitcoin's consensus security but lacking flexibility.
Meanwhile, sidechains  like Stacks or Layer 2 solutions, although they support smart contracts, still rely on independent multi-signature mechanisms for security, thus not fully inheriting the security of the Bitcoin mainnet.


## 3. System Architecture
![image](https://github.com/user-attachments/assets/04785c9a-0665-483f-a892-b257f4aec2d9)

### 3.1 System Architecture Overview
Super Bitcoin is a five-layer architecture protocol built by BEVM guided by the three problems of blockchain - decentralization, security and scalability.
This protocol is based on the Bitcoin protocol and utilizes the Lightning Network for efficient peer-to-peer communication. 
To extend the functionality of Lightning Network nodes, Super Bitcoin integrates Taproot Consensus and combines Bitcoin SPV, Schnorr signatures, MAST contracts, and a BFT PoS consensus mechanism to achieve scalable state management and transaction processing.
On this foundation, Super Bitcoin further integrates multiple virtual machines, including WASM, EVM, SVM, MoveVM, and CairoVM, creating a multi-chain system based on lightning chains that offer a diverse range of smart contract execution environments.
This modular framework significantly enhances the system's scalability and flexibility while maintaining the decentralized nature of the Bitcoin network. 
Importantly, all lightning chains share the Bitcoin network's consensus security, ensuring that the system remains highly secure as it scales.


## For more details, please see the [Super Bitcoin white paper](https://github.com/btclayer2/SuperBitcoin/blob/main/Super%20Bitcoin%20Whitepaper.pdf)
## 更多细节，请看[Super Bitcoin 中文白皮书](https://github.com/btclayer2/SuperBitcoin/blob/main/Super%20Bitcoin%20%E4%B8%AD%E6%96%87%E7%99%BD%E7%9A%AE%E4%B9%A6.pdf)
