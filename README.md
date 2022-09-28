# Installation
$ npm install @openzeppelin/contracts

#Usage
Once installed, you can use the contracts in the library by importing them:

pragma solidity ^0.8.0;

import "./ERC20.sol";

contract MyCollectible is ERC20 {
    constructor() ERC20("MyCollectible", "MCO") {
    }
}

If you're new to smart contract development, head to Developing Smart Contracts to learn about creating a new project and compiling your contracts.

To keep your system secure, you should #always# use the installed code as-is, and neither copy-paste it from online sources, nor modify it yourself. The library is designed so that only the contracts and functions you use are deployed, so you don't need to worry about it needlessly increasing gas costs.

