# Trust-Contract

This repository contains a Solidity smart contract named "Trust", demonstrating a simple use case of sending funds to a kid that can be withdrawn after a certain maturity time. It showcases how Solidity can be used to control fund transfer in Ethereum based on a certain condition (in this case, a time lock).

The contract Trust includes functionalities for adding a kid and specifying a time after which they can withdraw the funds. Only the contract creator, referred to as 'admin', can add kids. The contract also ensures that the funds can only be withdrawn after the set maturity time.

## Features
- Add a new kid and specify a time for maturity.

- Kids can withdraw their funds after the set maturity time.

- The contract creator (admin) has control over adding kids.

- Each kid can only be added once and the payment is also done only once.

- The maturity time is checked against the block.timestamp to ensure that funds are not withdrawn prematurely.

## Technologies Used
Solidity: Solidity is an object-oriented, high-level language for implementing smart contracts on the Ethereum Blockchain.

Remix: Remix IDE is a powerful open-source tool that helps you write Solidity contracts straight from the browser.

# Getting Started
## Prerequisites
- Familiarity with Solidity, Ethereum and smart contracts.

- A modern web browser capable of running Remix IDE.

## Using the Contract

- Step 1

  Open Remix IDE in your web browser.

- Step 2

  Click on the "+" icon on the top left to create a new file.

- Step 3

  Name the file (for instance, Trust.sol), and copy the contract code into the new file.

- Step 4

  To compile the contract, select Solidity Compiler from the Remix IDE plugins, select the appropriate compiler version (in
  this case, version 0.8.4) and click on Compile Trust.sol.

- Step 5

  To deploy the contract, select Deploy & Run Transactions from the Remix IDE plugins. From the environment dropdown menu,
  you can select JavaScript VM, Injected Web3 or Web3 Provider based on your preference.

- Step 6

  After deployment, the contract functions are accessible in the Deployed Contracts section. From here, the admin can add
  kids with their respective amounts and maturity times. Each kid can then withdraw their funds once the maturity time is
  reached.

# Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page.
