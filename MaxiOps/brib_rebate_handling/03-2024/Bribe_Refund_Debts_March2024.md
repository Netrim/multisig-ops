# Bribe rebates 

Bribe rebates will be 3% of the total amount of tokens Balancer sends specifically to Hidden Hand during each month. For example in this txn: https://etherscan.io/tx/0xff71dd036a7db0c9289722bd62b22bb9ac55cc12774571e8f5f03db5b719486c the total amount sent by the Balancer: Protocol Fees Multisig was 327,937.028191 USDC, however the net transfer to the Hidden Hand contract was 163,968.549999 USDC which is what the refund would be based on. 

### Asking for rebates    

The current process for requesting rebates is the collect the transactions from a given month from the [Protocol Fees Multisig](https://etherscan.io/address/0x7c68c42de679ffb0f16216154c996c354cf1161b) contract address on etherscan. Once the Maxis have the transactions they will totalize the amount send to [Hidden hand's contract address]((https://etherscan.io/address/0x7c68c42de679ffb0f16216154c996c354cf1161b) ) and share the transaction links, totaly bribe amount, and refund amount (bribes * 0.03) for the given month.

### Refunds December 2023 and January 2024

During these two months refunds were based on the total value of fees collected, not the 50% which is sent to Hidden Hand. This resulted in Hidden Hand overcompensating Balancer for these two months. December 2023's total was 625,182; 3% would be 18,755 [Dec 23 - 297245](https://etherscan.io/tx/0xfe2ed945144341979eabfc7c1b784b2696f51db6d6dbfaf5a8792dcc01d18b69) + [Dec 9 - 327937](https://etherscan.io/tx/0xff71dd036a7db0c9289722bd62b22bb9ac55cc12774571e8f5f03db5b719486c) which should have been a Net Transfer total to Hidden Hand of 312,591 and a refund of 9377.73. Hidden Hand did send the doubled amount as seen [here](0x34fb19f7c5f122362a729206a2b546c3f3a405b9e9f387ffe8be073fc944b7e6).

For January a similar scenario [Jan-20: 365,400](https://etherscan.io/tx/0xa81f07635a24b9660c174e27f4cf9ba03d14207089d822a195adeeb2a8d3fa03) and [Jan 5: 444254](https://etherscan.io/tx/0xd6d0689a995b7bdef50ff5f1ce2f05ac8b16ecc49e0309c9c9c05594c844d8c7) - 3% comes to 24289 USDC, however this should have been half resulting in 12144.5 net to Balancer in refund. The doubled amount was [received](0x9c16d7ec9e3bdf55048fa90579088e029676f9a6835d0ff780672b298c899202). 

To compensate Hidden Hand for the overdraft and not leave Balancer DAO in debt to their team we will forfeight bribe refunds until the total debt of 21,522 is paid. For February the total refund would be February correctly calculated is worth 9,533. 3% of [txn 1](https://etherscan.io/tx/0x4b7ce1295f1c3790f5a0353c13e93beb8a1d6c915bf9dd36fcfeb798a44f88d2) and [txn 2](https://etherscan.io/tx/0xb7bd4177a1fddd18364a52dc0563e5f3efde4856b97778477fb37d176be15000). This means Balancer will cover 11989 more USDC in refund debt before Hidden Hand begins to release more USDC to the DAO. 

### Update for Round dated March 2nd, 2024

Transaction: https://etherscan.io/tx/0x1c94e9e5b761e2167e1a204f0fb83cbf401cdea17cb162a88624383a718a1345 

Net Transfer to HH: 269405.73 - 3% of Transfer: 8082.17

Net Debt: **3907 USDC** = 11,989 - 8,082

### Update for Round dated March 16. 2024

Transaction: https://etherscan.io/tx/0xe4f7f58819101be2e1f01c172e1fe8491a3bdde81222ada61b82ba04f3e7e3ce

Net Transfer to HH: 374,274.269998 - 3% of Transfer: 11228.23

Net Debt:  **-7,321 USDC** = 3,907 - 11228.23 Balancer is back in the green. 

Rolling Bribe refund amount: 7,321 USDC.

### Final amount for March 2024 after March 29th round.

Transaction: https://etherscan.io/tx/0xfb123a687c777015c8ddc0079bd87469967908e7deec05348167c96a88d5a247

Net Transfer to HH: 384,335.299998 - 3% of Transfer: 11,530

Rolling bribe refund: 18,851 (11,530 + 7,321)

*Total bribe refund for March 2024: 18,851 USDC*