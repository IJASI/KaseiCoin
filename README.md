# KaseiCoin

## Installation

The code can be executed via the [Remix IDE website ](https://remix.ethereum.org/#optimize=false&runs=200&evmVersion=null&version=soljson-v0.8.7+commit.e28d00a7.js)


## Screenshots

Compile the completed code/file using the "0.5.5+commit.1d4f565a" compiler. 

The contracts must be deployed in the correct sequience in order to "link" them together. Firts deploy the crowdsale contract the coin contract after. See below addresses for the deployed contracts.

![FrontEnd](/images/Deployement_AtAddress.JPG)

Once the coin contract is deployed you will have access to capabilities such as addMinter, mint, decrease/increase allowance, and check balance. See screenshot showing a balance of 20 tokens. 

![FrontEnd](/images/Deployement_balanceOf_address.JPG)

See below how total current supply is also showing 20. 

![FrontEnd](/images/Deployement_balanceOf_totalSupplyJPG.JPG)

Once the code is updated for enhanced functionality you will be able to set a cap on the coing and/or set a goal to be reached in the crowdsale. Please see below screenshot sowing the goal set of 300 ether. 

![FrontEnd](/images/Deployement_call_balanceOf.JPG)

The below screeshot shows the the balance of 300, the cap set of 300, and cap reached updated to True. 

![FrontEnd](/images/Deployement_crowdsale_goal.JPG)

![FrontEnd](/images/Deployement_weiRaisedJPG)

![FrontEnd](/images/Deployment_buyTokens_balanceOf.JPG)

![FrontEnd](/images/Deployment_Contract_addMinter_balanceOf.JPG)

![FrontEnd](/images/Deployment_crowds_token_buyToken.JPG)

![FrontEnd](/images/Deployment_injectedWeb3_Contract_KaseiCoin_AtAddress.JPG)



Once in the deployment page you should see the name of your file on the contract box. 

![FrontEnd](/images/contract_name_deploy.JPG)

Once you click deploy you should see your Metamask account pop up. You may then confirm the contract deployment. 

![Transactions_detail](/images/deploy_metamask_Ganacheacc.JPG)

Once the contract is deployed you should be able to scroll down on the left side menu and enter the transaction value. 

![Transactions_detail](/images/TRANS1A.JPG)

On the side menu you will be able to see information such as the contract balance, last to withdraw, etc. 

![Transactions_detail](/images/TRANS1B.JPG)

The [Ethereum Unit Converter]( https://eth-converter.com/) can be used in order to update the correct Wei amount you intend to transact with. 

![Transactions_detail](/images/TRANS1C.JPG)

Once you are ready to initiate a transaction on the left side menu scroll down to the "Transact" box and click it. 

![Transactions_detail](/images/TRANS2B.JPG)

Once the transact button is clicked the MetaMask wallet extension will once again open this time it will show the balance on the account and the amount  of the transaction you are initiating.

![Transactions_detail](/images/TRANS3A.JPG)

Please find below a sample of the tranaction hases made via the joint saving account contract. The trancations were in the folliwing denominations. 

Transaction 1: Send 1 ether as wei.

Transaction 2: Send 10 ether as wei.

Transaction 3: Send 5 ether.


![Transactions_detail](/images/Ganache_TX.JPG)

## Demo

If you still have any doubts please watch the following video demo.




https://user-images.githubusercontent.com/85713622/141889382-f5bbbbec-6efc-4a37-8d69-8aabb0fd3d27.mp4





## Contributors(ing)
This a project designed by:

Jose Sampedro
sampedro.jose.a@gmail.com

With the contributions and assistance of:

The Columbia Fintech Bootcamp TAs and Tutors.

## License

[See GNU v3.0](https://github.com/IJASI/Challenge-3/blob/491335d4123fae396530363cb79be7070e049796/LICENSE)

