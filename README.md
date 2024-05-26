# EVM Subnet Setup for DeFi Kingdom Clone

Welcome to the guide for setting up your custom EVM subnet on the Avalanche network. Follow these steps to define your native currency, connect to MetaMask, and deploy the essential building blocks for your DeFi Kingdom clone.

## Table of Contents
1. [Introduction](#introduction)
2. [Prerequisites](#prerequisites)
3. [Setting Up Your EVM Subnet](#setting-up-your-evm-subnet)
4. [Defining Your Native Currency](#defining-your-native-currency)
5. [Connecting to MetaMask](#connecting-to-metamask)
6. [Deploying Basic Building Blocks](#deploying-basic-building-blocks)
7. [Resources](#resources)

## Introduction
This guide provides detailed instructions on creating a custom EVM subnet on the Avalanche network, defining your native currency, connecting to MetaMask, and deploying smart contracts essential for your DeFi Kingdom clone.

## Prerequisites
- Basic understanding of blockchain and smart contracts
- Node.js and npm installed
- MetaMask wallet installed
- Familiarity with Solidity and Remix IDE

## Setting Up Your EVM Subnet
To create a custom EVM subnet on the Avalanche network, follow the comprehensive steps outlined in our guide and the [Avalanche documentation](https://docs.avax.network).

1. **Install Avalanche-CLI:** 
   ```bash
   npm install -g avalanche-cli
   ```
2. **Initialize the EVM Subnet:**
   ```bash
   avalanche subnet create <your-subnet-name>
   ```
3. **Configure the Subnet:**
   Edit the configuration files to set your parameters.

## Defining Your Native Currency
You can establish your native currency to be used as the in-game currency for your DeFi Kingdom clone.

1. **Modify Subnet Configuration:**
   Add the native currency parameters in your subnet configuration file.
2. **Deploy the Subnet:**
   ```bash
   avalanche subnet deploy <your-subnet-name>
   ```

## Connecting to MetaMask
To connect your EVM subnet to MetaMask, follow these steps:

1. **Obtain RPC URL:**
   After deploying your subnet, you'll receive an RPC URL.
2. **Add Network to MetaMask:**
   - Open MetaMask and go to Settings > Networks > Add Network.
   - Enter the RPC URL, Chain ID, and other details.

For a detailed walkthrough, refer to our guide.

## Deploying Basic Building Blocks
Utilize Solidity and Remix to deploy the smart contracts necessary for your game.

1. **Open Remix IDE:**
   Go to [Remix IDE](https://remix.ethereum.org/).
2. **Write Smart Contracts:**
   Create contracts for battling, exploring, and trading. Example:
   ```solidity
   pragma solidity ^0.8.0;

   contract Battle {
       // Battle logic here
   }
   ```
3. **Compile and Deploy Contracts:**
   Compile your contracts in Remix and deploy them using the MetaMask network you connected to earlier.

## Resources
- [Avalanche Documentation](https://docs.avax.network)
- [Remix IDE](https://remix.ethereum.org/)
- [MetaMask](https://metamask.io/)

For further assistance, refer to our detailed guide and the official Avalanche documentation. Enjoy building your DeFi Kingdom clone!
