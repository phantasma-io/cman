# Cman (Smart contract Deployer)
Cman is a smart contract deployer for the Phantasma Chain.

## Attributes
All the attributes that can be used.
* `--contract <value>` -> attribute to select the path to the contract .pvm (`/path/to/some/contract.pvm`).
* `--rpc-url <value>` -> attribute to select the rpc url.
* `--nexus <value>` -> attribute to select the nexus name.
* `--token` -> attribute to deploy if the smart contract is a token
* `--update` -> attribute to update the smart contract previously deployed

## How deploy a smart contract via Cman

Example:
`./cman deploy --contract /path/to/some/contract.pvm --rpc-url http://localhost:5101/rpc --nexus simnet --token`

