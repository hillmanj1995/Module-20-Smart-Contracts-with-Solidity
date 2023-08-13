# Module 20 Chellange: Joint Accounts with Solidity

The analyst has recently been hired by a fintech startup. This company is disrupting the finance industry with its own cross-border, Ethereum-compatible blockchain that connects financial institutions. Currently, the team is building smart contracts to automate many of the institutions’ financial processes and features, such as hosting joint savings accounts.

To automate the creation of joint savings accounts, the analyst created a Solidity smart contract that accepts two user addresses. These addresses were able to control a joint savings account. The smart contract used ether management functions to implement a financial institution’s requirements for providing the features of the joint savings account. These features consisted of the ability to deposit and withdraw funds from the account.

## Summary

Using remix the analyst compiled and deployed their smart contract into the Remix VM (london) environment which allows the analyst to run the contract's functions:

![deployed_contract.png](https://github.com/hillmanj1995/Module-20-Smart-Contracts-with-Solidity/blob/main/Challenge/Execution_Results/deployed_contract.png)

Once the contract was successfully deployed, the analysted tested the withdraw function by withdrawing 20 Ether into the primary account:

![deposit.png](https://github.com/hillmanj1995/Module-20-Smart-Contracts-with-Solidity/blob/main/Challenge/Execution_Results/deposit.png)

After confirming that the deposit function worked, the analyst set the accounts that the ether will be transferred between:

![setaacounts.png](https://github.com/hillmanj1995/Module-20-Smart-Contracts-with-Solidity/blob/main/Challenge/Execution_Results/setaacounts.png)

With the accounts set, the analyst tested the withdrawl function by transferring the amounts of 1, 5, and 10 Ether between the acocunts:

1 Eth:

![1_eth_withdraw.png](https://github.com/hillmanj1995/Module-20-Smart-Contracts-with-Solidity/blob/main/Challenge/Execution_Results/1_eth_withdraw.png)

5 Eth:

![5_eth_withdraw.png](https://github.com/hillmanj1995/Module-20-Smart-Contracts-with-Solidity/blob/main/Challenge/Execution_Results/5_eth_withdraw.png)

10 Eth:

![10_eth_withdraw.png](https://github.com/hillmanj1995/Module-20-Smart-Contracts-with-Solidity/blob/main/Challenge/Execution_Results/10_eth_withdraw.png)

