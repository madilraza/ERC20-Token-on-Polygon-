# ERC20-Token-on-Polygon-
Create your ERC20 Standard Token  Easily deploy Smart Contract for a Standard, Capped, Mintable, Burnable, Payable ERC20 Token on Ethereum, Polygon, Binance Smart Chain Networks.  No login. No setup. No coding required.


# Guide: How to Create a Polygon Token in 5 Steps
<p align="left"> <img src="https://pbs.twimg.com/media/FHnzKi8X0AM6cFH?format=jpg&name=small" alt="madilraza" /> </p>

## How to Create a Polygon Token in 5 Steps

Now that we have a node, changed our MetaMask network, and have some MATIC, we can move on to the main topic of this article. Creating a Polygon token is easy, and we can do so through the following five steps: 1) create a Remix file, 2) acquire a template from OpenZeppelin, 3) develop the contract, 4) compile the contract, and finally, 5) deploy the token.

# 1. Create a New Remix File

The first step of the process is to launch Remix by clicking the following link: remix.ethereum.org. Remix is an IDE or integrated development environment for Ethereum development. The IDE is great for developing smart contracts and provides functionalities for developing, compiling, and deploying Solidity-based contracts.
On initial launch, Remix will already have a default workspace set up. This workspace will contain a few folders for contracts, scripts, and tests. If we open the contracts folder, we’ll see already developed smart contracts that we can inspect to overview how a contract might look. However, for this example, we are simply going to right-click the contracts folder and hit ”New File”. This will create a completely new contract that we can name whatever we want. As we are creating a token, we’ll name this file ”Token.sol”. The ”.sol” is important as this specifies that the contract will be written using the Solidity programming language.



# Choose from these Token types for your needs.
What are your requirements?

Detailed

Your Token will be fully compliant with the ERC20 definition and compatible with any ERC20 wallet all around the world. It will have a name, a symbol and a decimals amount.
Burnable

Your Token can be burnt. It means that you can choose to reduce the circulating supply by destroying some of your tokens.
Mintable

You will be able to generate tokens by minting them. Only token owner will be able to mint. You can also disable minting if you don’t want to generate tokens anymore.
Pausable

Your Token transfer can be paused. Useful to prevent trades until a period or freezing all token transfers.
Ownable Access

Your Token will have an Owner. Token owner will be able to mint new tokens or to call the finish minting function.
Role Based Access

Your Token will have Roles. You can add or remove ADMIN or MINTER role to addresses. Your token will be Ownable too.
Capped

You won't be able to generate more tokens than the defined token cap. This ensure people that you will not generate more tokens than declared.
ERC1363 Payable Token

The ERC1363 is an ERC20 compatible Token that can make a callback on the receiver contract to notify token transfers or token approvals.
Token Recover

There are lots of tokens lost forever into Smart Contracts. It allows the contract owner to recover any ERC20 token sent into the contract for error.
