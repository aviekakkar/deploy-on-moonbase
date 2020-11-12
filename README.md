
🧑‍💻 [ECOSYSTEM CHALLENGE] Deploy on Moonbase Alpha using Truffle

## Challenge description
This challenge focuses on using Truffle, a widely used developer tool in Ethereum, to deploy an ERC20 token contract to Moonbase Alpha (Moonbeam TestNet). Funds for deployment can be requested from the Faucet set up in our Moonbeam's Discord channel.

You need to configure Truffle to connect to Moonbase Alpha.

### Submission requirements
The submitted result is the address of the migrations contract (normally deployed by Truffle) and the address of the ERC20 token contract. Please submit them separated by a comma, that is: migrationsAddress,tokenAddress

The verification process will check, using the provided addresses, that the owner of the Migrations contract is the same as the owner of the ERC20 token totalSupply. It will also check for a standard ERC20 token structure, with the standard methods such as name, symbol, decimals and totalSupply.

### Resources
In our Docs Website you will find lots of information available:

- Truffle
- Connect to Moonbase
- Moonbase Faucet
