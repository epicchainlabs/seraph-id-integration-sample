<p align="center">
  <img
      src="http://www.seraphid.io/assets/img/logo-dark.png"
      width="450px"
      alt="Seraph ID Logo">
</p>

<h1 align="center">
  **Seraph ID Integration Sample**
</h1>

<p align="center">
  **A Comprehensive Demonstration of Seraph ID Integration and Usage**
</p>

<p align="center">      
  <a href="https://github.com/epicchainlabs/seraph-id-integration-sample/blob/master/LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg?color=green" alt="MIT License">
  </a>
</p>

# Overview

Welcome to the **Seraph ID Integration Sample** repository! This project serves as a thorough example implementation of Seraph ID, a cutting-edge self-sovereign identity solution on the EpicChain blockchain platform. This demo is designed to illustrate the integration and practical application of Seraph ID features, including wallet management, claims issuance, verification, and more.

Seraph ID empowers individuals with a self-sovereign identity system that allows them to securely and transparently control their personal data on the EpicChain blockchain. By utilizing this demo, you will gain insights into how to effectively leverage Seraph ID’s functionalities in your own applications, showcasing real-world use cases and best practices.

The integration sample demonstrates how to manage Seraph ID wallets, create and verify claims, and interact with the blockchain. Whether you are a developer looking to explore the capabilities of Seraph ID or a stakeholder interested in self-sovereign identity solutions, this demo provides a solid foundation to get started.

To delve deeper into the concepts of self-sovereign identity and explore additional resources related to Seraph ID, please visit the [Seraph ID](http://www.seraphid.io/) official web page.

# Getting Started with the Demo

To run the Seraph ID demo and see it in action, follow these detailed steps:

### Prerequisites

Before you begin, ensure that you have the following software installed on your development machine:

- **Node.js**: It is recommended to use the latest Long-Term Support (LTS) version of Node.js to ensure compatibility with the demo.
- **Yarn**: Yarn is a package manager that we use for dependency management. Ensure you have Yarn version 1.16.0 or higher installed.

### Installation Steps

1. **Clone the Repository:**

   Begin by cloning the repository to your local machine using Git. This will create a local copy of the demo project:

   ```bash
   git clone https://github.com/swisscom-blockchain/seraph-id-demo.git
   cd seraph-id-demo
   ```

2. **Install Dependencies:**

   Use Yarn to install all the necessary dependencies for the project. This step will ensure that you have all the required libraries and packages:

   ```bash
   yarn
   ```

3. **Build the Project:**

   After installing dependencies, build the project to compile the TypeScript code and prepare the demo for running:

   ```bash
   yarn build
   ```

### Running the Demo

You can start the demo using either of the following methods:

#### Method 1: Using ts-node and Yarn

1. **Bootstrap the Project:**

   Run the bootstrap script to set up the environment and prepare the demo for execution:

   ```bash
   ts-node bootstrap/bootstrap.ts
   ```

2. **Navigate to the Demo Directory:**

   Change to the `demo` directory where the demo application resides:

   ```bash
   cd demo
   ```

3. **Start the Demo:**

   Launch the demo application using Yarn. This will start a local development server and open the demo in your default web browser:

   ```bash
   yarn start
   ```

#### Method 2: Using Makefile

1. **Run the Bootstrap Script:**

   Alternatively, you can use the Makefile to run the bootstrap script:

   ```bash
   make run-script
   ```

2. **Start the Demo:**

   Use the Makefile to start the demo application:

   ```bash
   make start-demo
   ```

### Customizing the Demo

The provided demo serves as a basic template to get you started with Seraph ID. You can customize and extend the demo to fit your specific use cases by modifying the TypeScript and React code within the `src` directory. This includes adding new features, adjusting UI components, or integrating additional functionality.

# Contributing to the Project

We encourage contributions from the community to enhance and expand the Seraph ID Integration Sample. If you would like to contribute, please follow the guidelines below:

## Setup for Development

This repository uses TypeScript and React, managed with Yarn. Ensure you have the following tools installed on your development environment:

- **Yarn**: Version 1.16.0 or higher.
- **Node.js**: Latest LTS version.

To set up your development environment:

1. **Clone the Repository:**

   Clone the repository to your local machine:

   ```bash
   git clone https://github.com/swisscom-blockchain/seraph-id-demo.git
   cd seraph-id-demo
   ```

2. **Install Dependencies:**

   Use Yarn to install the project dependencies:

   ```bash
   yarn
   ```

3. **Build the Project:**

   Compile the TypeScript code and build the project:

   ```bash
   yarn build
   ```

## Running Tests

Before running tests, ensure that:

- **Smart Contracts:** The Issuer and RootOfTrust smart contracts must be deployed on your blockchain network.
- **Test Data:** Network configurations and test data should be accurately maintained in the `__tests__/test-data.json` file.

To execute unit tests and verify the functionality of the demo:

```bash
yarn test
```

This command will run all the unit tests and check the correctness of the implementation.

# References and Resources

For additional information and resources related to Seraph ID, please refer to the following links:

- **[Seraph ID Official Page](http://www.seraphid.io):** Visit the official site to learn more about Seraph ID, its features, and its impact on self-sovereign identity.
- **[Seraph ID SDK on GitHub](https://github.com/epicchainlabs/seraph-id-integration-sample):** Access the JavaScript SDK repository for tools and libraries related to Seraph ID integration.
- **[Seraph ID Smart Contract Templates on GitHub](https://github.com/swisscom-blockchain/seraph-id-smart-contracts):** Review smart contract templates and examples for implementing Seraph ID solutions on the EpicChain blockchain.
- **[Seraph ID Chrome Extension on GitHub](https://github.com/swisscom-blockchain/seraph-id-chrome-extension):** Download and explore the Seraph ID extension for Chrome, which enhances the user experience with additional features.
- **[Seraph ID DID Resolver on GitHub](https://github.com/swisscom-blockchain/seraph-id-did-driver):** Integrate with the Seraph ID DID resolver for managing decentralized identifiers (DIDs) effectively.

# License Information

The **Seraph ID Integration Sample** is licensed under the [MIT License](https://github.com/epicchainlabs/seraph-id-integration-sample/blob/master/LICENSE). This open-source license allows you to freely use, modify, and distribute the demo code while adhering to the terms of the MIT License.
