# KaseiCoin

## Installation

The code can be executed via the [Remix IDE website ](https://remix.ethereum.org/#optimize=false&runs=200&evmVersion=null&version=soljson-v0.8.7+commit.e28d00a7.js)


## Screenshots

Compile the completed code/file using the "0.5.5+commit.1d4f565a" compiler. Once the contracts are successfully compiled make sure you are deploying the contracts in the Injected web3 enviroment. 

![FrontEnd](/images/Deployment_injectedWeb3_Contract_KaseiCoin_AtAddress.JPG)

The contracts must be deployed in the correct sequience in order to "link" them together. Firts deploy the crowdsale contract the coin contract after. See below addresses for the deployed contracts.

![FrontEnd](/images/Deployement_AtAddress.JPG)

Once the coin contract is deployed you will have access to capabilities such as add+Minter, mint, decrease/increase allowance, and check balance. See screenshot showing a balance of 20 tokens. 

![FrontEnd](/images/Deployement_balanceOf_address.JPG)

See below screenshot for sample of the KaseiCoinCrowdsale contract deployed and setting address to buy tokens. 

![FrontEnd](/images/Deployment_crowds_token_buyToken.JPG)

See below how total current supply is also showing 20. 

![FrontEnd](/images/Deployement_balanceOf_totalSupplyJPG.JPG)

Once the code is updated for enhanced functionality you will be able to set a cap on the coin and/or set a goal to be reached in the crowdsale. Please see below screenshot sowing the goal set of 300 wei.

![FrontEnd](/images/Deployement_call_balanceOf.JPG)

The below screeshot shows the the balance of 300, the cap set of 300, and cap reached updated to True. 

![FrontEnd](/images/Deployement_crowdsale_goal.JPG)

## Contributors(ing)
This a project designed by:

Jose Sampedro
sampedro.jose.a@gmail.com

With the contributions and assistance of:

The Columbia Fintech Bootcamp TAs and Tutors.

## License

[See GNU v3.0](https://github.com/IJASI/Challenge-3/blob/491335d4123fae396530363cb79be7070e049796/LICENSE)

