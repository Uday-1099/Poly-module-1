# Poly-module-1

## BIKES - NFT Contract for Super Bikes Collection

The BIKES smart contract is an Ethereum-based NFT (Non-Fungible Token) collection that represents a collection of Super Bikes as digital assets. This contract is built on the ERC-721 standard, which allows for the creation and management of unique, indivisible tokens. Each token represents ownership of a specific Super Bike in the collection.

## Features
# Max Quantity: The contract allows the creation of a maximum of 5 NFTs representing different Super Bikes.

# Owner Control: The contract creator is designated as the owner and has exclusive control over certain functions.

# Minting: The owner can mint new NFTs by specifying the quantity. Minting is the process of creating new tokens and assigning ownership to the minter.

# Base URL: The base URL for the NFT metadata is set to a specific IPFS gateway, which hosts the metadata for each NFT. This metadata includes information about the Super Bike represented by the NFT.

# Prompt Description: The contract provides a prompt description, which is publicly accessible and describes the theme or concept of the NFT collection.


### Functions

# Constructor
The constructor initializes the contract and sets the initial owner. It also configures the base name and symbol for the NFTs.

# Modifier: onlyOwner
This modifier restricts certain functions to be executed only by the owner of the contract. Only the owner can mint new NFTs.

# Mint Function
The mint function allows the owner to mint new NFTs. The owner can specify the quantity of tokens to mint. The function ensures that the total supply of NFTs does not exceed the maximum quantity set in the contract.

# Base URI Function
The _baseURI function is overridden to provide the base URL for the NFT metadata. This URL is used as a prefix to construct the full URL for each NFT's metadata.

# Prompt Description Function
The promptDescription function returns the prompt description of the NFT collection. This description provides insights into the theme or concept behind the Super Bikes NFT collection.

## Deployment
To deploy the BIKES contract, follow these steps:

Ensure you are connected to an Ethereum-compatible blockchain network.
Deploy the contract with the specified Solidity compiler version (^0.8.0) and provide the necessary constructor parameters.
Interacting with the Contract
The owner of the contract can mint new NFTs using the mint function.
The promptDescription function can be called to retrieve the prompt description of the NFT collection.
NFT metadata can be retrieved by combining the base URL and the token ID.

# Disclaimer
This code is provided as-is and for educational purposes only. Make sure to review and test the code thoroughly before deploying it on the Ethereum network. Keep in mind that blockchain transactions are irreversible, and mistakes can result in financial losses.

License
This smart contract is released under the MIT License. You can find the license text at the beginning of the contract code.

This document provides an overview of the BIKES NFT contract functionality and deployment. It does not cover potential security audits or detailed usage instructions. Consult the official Solidity documentation and relevant resources for a comprehensive understanding of smart contracts and NFTs.





