# MyERC20.sol-and-MyERC721.sol
ERC20 and ERC721 token contracts to keep track of fungible and non-fungible tokens

Quickstart with OpenZeppelin wizard

Overview about Ethereum Improvement Proposals (EIPs)
Overview about Application-level standards and conventions (ERCs)
Explain about OpenZeppelin Contracts library
(Review) Objects in smart contracts
Inheritance overview
Overview about ERC20
Overview about ERC721
Using OpenZeppelin wizard

References

https://eips.ethereum.org/

https://eips.ethereum.org/erc

https://docs.openzeppelin.com/contracts/4.x/

https://docs.openzeppelin.com/contracts/4.x/erc20

https://docs.openzeppelin.com/contracts/4.x/erc721

https://docs.soliditylang.org/en/latest/contracts.html#inheritance

https://solidity-by-example.org/inheritance/

https://docs.openzeppelin.com/contracts/4.x/wizard

Plain ERC20 Code reference
    // SPDX-License-Identifier: MIT
    pragma solidity >=0.7.0 <0.9.0;

    import "@openzeppelin/contracts/token/ERC20/ERC20.sol";

    contract MyToken is ERC20 {
        constructor() ERC20("MyToken", "MTK") {}
    }

Plain ERC721 Code reference
    // SPDX-License-Identifier: MIT
    pragma solidity >=0.7.0 <0.9.0;

    import "@openzeppelin/contracts/token/ERC721/ERC721.sol";

    contract MyToken is ERC721 {
        constructor() ERC721("MyToken", "MTK") {}
    }

Contract structure
Syntax about inheritance
Overview about OpenZeppelin features for ERC20 and ERC721
Overview about OpenZeppelin features for Access Control
Overview about OpenZeppelin utilities and components
Adding minting feature
Adding RBAC feature

References

https://www.npmjs.com/package/@openzeppelin/contracts

https://docs.openzeppelin.com/contracts/4.x/extending-contracts

https://docs.openzeppelin.com/contracts/4.x/access-control

Operating the contracts with scripts
(Review) Script operation
(Review) Accounts and funding
(Review) Providers
(Review) Async operations
(Review) Running scripts on test environment
(Review) Contract factory and json imports
(Review) Transaction receipts and async complexities when running onchain
Events with solidity
Event syntax
Event storage
Event indexing
Topics and filters
Transaction structure
State changes with events

References

https://docs.soliditylang.org/en/latest/contracts.html#events

https://docs.ethers.org/v6/api/contract/#ContractEventName

https://docs.ethers.org/v6/api/contract/#BaseContract-on

https://docs.ethers.org/v6/api/contract/#BaseContract-queryFilter

Watching for events in tests
Event syntax with Hardhat Chai Matchers
Triggering an event
Checking arguments

References

https://hardhat.org/hardhat-chai-matchers/docs/overview#events

