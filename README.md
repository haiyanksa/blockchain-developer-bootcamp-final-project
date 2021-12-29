# blockchain-developer-bootcamp-final-project
Repository for Consensys blockchain developer bootcamp final project

**Atomic Swap web page**

The project is about building a DAPP web page to facilitate atomic swap of ERC-20 token and ERCERC-1404 (security token).

**Atomic Swap Contract Workflow:**

1. One user has an ERC20 token (user A). Another user has an ERC1404 (user B). This can be on the same network or on different EVM network (such as Ethereum and BSC)
2. Users visit the atomic swap web page. It detects and displays the user balance of ERC20 and ERC1404
3. User A sends ERC20 token to user B via the atomic swap function to swap it for ERC1404. ERC20 will be locked
4. User B sends ERC1404 token to user A via the atomic swap function to swap it for ERC1404. ERC1404 will be locked
5. Only when both A and B sends their tokens, the smart contract will release the tokens
