# LoldexProtocol

Loldex is an open protocol that facilitates trustless, purely smart contract driven, low friction exchange of Ethereum-based assets. 
For more information on how it works, check out the protocol specification.

This repository protocol smart contracts and numerous developer tools. If you're developing on 0x now or are interested in using infrastructure in the future, 
please join our developer mailing list for updates on our website www.loldex.io

You can propose LIPs - Loldex improvement proposals and contribute 

## Developed Smart Contracts 

### LOLB Token Burn  
Smart contract that burns LOLB tokens when trade is completed
https://ropsten.etherscan.io/tx/0xb6bb4d3a7a96fd3fd5774b4e1f9463341c18b4a6c1150bb4312634f38808a8c2
### LOLB WETH 
Our own WETH variant to trade ETH
### LOLB Basic Exchange Mechanism
Basic Smart contract to trade and support our front end 

## Other contracts under development
These contracts are currently being developed by core devs and contributors

### LOLB Fast Orderbook and Audit Sidechain
Smart contracts to improve the exchange mechanism and features. Will be pubic-private blockchain model 
### LOLB IEO Listing and Liqudiity Pool
Smart contract to run your own Initial Exchange Offering or run your own liquidity pool. Will be pubic-private blockchain model 
### LOL Bitcoin Cash Sidechain and LOLB SLP 1:1 Token  
Smart contract to pair with Bitcoin Cash SLP tokens. May expand features to other aspects. Dependent on Bitcoin Cash blockchain and utilities 
https://github.com/simpleledger/Electron-Cash-SLP
https://github.com/simpleledger/slp-specifications

## LIPs LOLDEX Improvement Proposals

Inspired by Ethereum Improvement Proposals (EIPs) describe standards for the Ethereum platform, including core protocol specifications, client APIs, and contract standards, LOLDEX has its own LIPs 
 

### Contributing

Review LIP-1.
Fork the repository by clicking "Fork" in the top right.
Add your LIP to your fork of the repository.  
Submit a Pull Request to LOLDEX repository.
Your first PR should be a first draft of the final. It must meet the formatting criteria enforced by the build (largely, correct metadata in the header). An editor will manually review the first PR for a new LIP and assign it a number before merging it. Make sure you include a discussions-to header with the URL to a discussion forum or open GitHub issue where people can discuss.

If it requires images, the image files should be included in a subdirectory of the assets folder for that as follow: assets/lip-X (for lip X). When linking to an image in the EIP, use relative links such as ../assets/lip-X/image.png.


### LIP Status Terms

Draft - first publish undergoing rapid iteration and changes
Last Call - ready for review by a wide audienc
Accepted - LIP that the Core Devs have decided to implement 
Deferred - not being considered for immediate adoption. May be reconsidered in the future 
 
