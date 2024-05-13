# hardhat-subjektify

**Hardhat plugin for integrating Subjektify's Subject-Oriented Programming into your blockchain development workflow.**

[Hardhat](https://hardhat.org) is a popular development framework for Ethereum, known for its extensibility and flexibility. `hardhat-subjektify` enhances Hardhat by enabling Subject-Oriented Programming features, streamlining the development process of decentralized applications (dApps).

## What

`hardhat-subjektify` is a Hardhat plugin designed to incorporate the Subject-Oriented Programming paradigm into your smart contract development environment. This integration allows developers to define, manage, and deploy smart contracts more effectively by leveraging the advanced structuring capabilities of Subjektify within the Hardhat ecosystem.

## Installation

Follow these steps to install `hardhat-subjektify` in your Hardhat project:

```bash
npm install hardhat-subjektify
```

Add the plugin to your `hardhat.config.js`:

```js
require("hardhat-subjektify");
```

Or, if you are using TypeScript, add this line to your `hardhat.config.ts`:

```ts
import "hardhat-subjektify";
```

## Required plugins

This plugin works in conjunction with the following Hardhat plugins:

- [@nomiclabs/hardhat-ethers](https://github.com/nomiclabs/hardhat/tree/master/packages/hardhat-ethers) (or any Ethereum provider plugin like `hardhat-web3`)

## Tasks

This plugin does not introduce new tasks to Hardhat; instead, it enhances existing compile and deploy tasks by integrating Subjektify’s capabilities directly into your smart contract development lifecycle.

## Environment extensions

`hardhat-subjektify` extends the Hardhat Runtime Environment by adding a `subjektify` field, which provides access to Subjektify's tools and functionalities directly within your Hardhat tasks, scripts, and tests.

## Configuration

To configure `hardhat-subjektify`, add a `subjektify` section in your `hardhat.config.js` or `hardhat.config.ts`. Here's an example of basic configuration:

```js
module.exports = {
  subjektify: {
    defaultSubject: "ExampleSubject",
  }
};
```

## Usage

Once installed and configured, `hardhat-subjektify` allows you to utilize Subject-Oriented Programming principles seamlessly as part of your Hardhat project workflow. There is no need for additional setup steps—just continue developing your smart contracts with enhanced structure and organization provided by Subjektify.

For more detailed information on how to leverage the full power of Subject-Oriented Programming in your dApp development, consult the Subjektify documentation linked within your Hardhat project environment or on the Subjektify official website.
