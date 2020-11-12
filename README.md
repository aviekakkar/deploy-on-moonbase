# Submission

0x53580D18Cf66c25034ba1c7265C3A33B79B877FC,0xF0dfc1138965596Ce8523Cc80a830A321Bb39A90

---
Migration address: 0x53580D18Cf66c25034ba1c7265C3A33B79B877FC

ERC20 address: 0xF0dfc1138965596Ce8523Cc80a830A321Bb39A90

Deployer/Owner: 0xf5d428862E4B278e051DE85D740447705217D518

---
```
❯ truffle migrate --network moonbase

Compiling your contracts...
===========================
> Everything is up to date, there is nothing to compile.



Starting migrations...
======================
> Network name:    'moonbase'
> Network id:      43
> Block gas limit: 0 (0x0)


1_initial_migration.js
======================

   Deploying 'Migrations'
   ----------------------
   > transaction hash:    0x0b5b8018914269f2e6663a0bb4f96b505d44848af6aac16e025fa989962f7070
   > Blocks: 0            Seconds: 8
   > contract address:    0x53580D18Cf66c25034ba1c7265C3A33B79B877FC
   > block number:        349547
   > block timestamp:     1605190764
   > account:             0xf5d428862E4B278e051DE85D740447705217D518
   > balance:             9.95244766
   > gas used:            164163 (0x28143)
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.00328326 ETH


   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:          0.00328326 ETH


2_deploy_contracts.js
=====================

   Deploying 'MyToken'
   -------------------
   > transaction hash:    0x29ea03185fec25d9f2005a8a3d8dce89011078834321cd98e199023d5cafec2c
   > Blocks: 1            Seconds: 12
   > contract address:    0xF0dfc1138965596Ce8523Cc80a830A321Bb39A90
   > block number:        349551
   > block timestamp:     1605190800
   > account:             0xf5d428862E4B278e051DE85D740447705217D518
   > balance:             9.9294675
   > gas used:            1106667 (0x10e2eb)
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.02213334 ETH


   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:          0.02213334 ETH


Summary
=======
> Total deployments:   2
> Final cost:          0.0254166 ETH
```

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
