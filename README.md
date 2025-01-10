AI Model Marketplace App

Members: 
1.Zhansarin Akan SE-2322
2.Zhumabek Meiirzhan SE-2330
3.Serikov Darkhan SE-2330

Overview

The AI Model Marketplace dApp is a decentralized application that enables users to list, purchase, and rate AI models. The application leverages smart contracts for secure and transparent management of the marketplace and includes an intuitive web interface for user interaction.

Features

List AI Models: Allows users to add AI models with a name, description, and price.

Purchase AI Models: Enables users to buy AI models securely using blockchain transactions.

Rate AI Models: Users can rate purchased AI models to contribute to their overall rating.

Withdraw Funds: Model creators can withdraw their earnings from sales.

View Model Details: Retrieve and display details of any AI model.

Usage

Prerequisites

Node.js installed

Truffle suite set up

Ganache running as a local blockchain

Metamask browser extension configured

Steps to Use

Clone the Repository:

git clone <repository-link>
cd ai-model-marketplace

Install Dependencies:

npm install

Compile and Deploy Smart Contracts:

truffle compile
truffle migrate --network development

Run Frontend:

npm start

Interact with the dApp:

Open the web application in your browser.

Use Metamask to connect your wallet.

List, purchase, rate, or view AI models.

Team Members

Alice Johnson - Backend Developer

Bob Smith - Frontend Developer

Charlie Lee - Blockchain Specialist

Demo





Examples

Example: Listing a Model

Function: listModel(string memory name, string memory description, uint256 price)

Input:

Name: "Image Classifier"

Description: "A pre-trained model for image classification."

Price: 0.05 ETH

Example: Purchasing a Model

Function: purchaseModel(uint256 modelId)

Input:

Model ID: 1

Example: Rating a Model

Function: rateModel(uint256 modelId, uint8 rating)

Input:

Model ID: 1

Rating: 5

Repository Structure

.
├── contracts
│   └── Marketplace.sol
├── migrations
│   └── 1_deploy_contracts.js
├── src
│   ├── components
│   │   └── ListModelForm.js
│   ├── App.js
│   └── index.js
├── public
│   └── demo
│       ├── list_model.png
│       ├── purchase_model.png
│       └── rate_model.png
├── package.json
├── truffle-config.js
├── README.md
└── LICENSE

License

This project is licensed under the MIT License. See the LICENSE file for details.

References

Web3.js Documentation

Smart Contracts Guide

Ganache Blockchain

Using Ganache with Remix and Metamask

