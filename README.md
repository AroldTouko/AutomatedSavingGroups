# AutomatedSavingGroups
An DApp to automate a saving group using smart contracts
1. To test this project, you have to import this code on Remix IDE (https://remix.ethereum.org/)
2. After it you should create some Celo Alfajores test account by first connecting your Metamask Browser Wallet to the Alfajores test Network (see a tutorial here : https://medium.com/defi-for-the-people/how-to-set-up-metamask-with-celo-912d698fcafe)
3. You have to fund each account with test CELO and cUSD by using a faucet (https://celo.org/developers/faucet)
4. Next you must compile the contract and deploy it with the Injected Provider Metamask
5. In order to test the contracts, you should follow this order : 
    * create a saving group (this automatically create a group of members with the caller address as the first group member). Note that this group is binded to the     
      created Saving Group 
    * Create Members 
    * Add members to a group (the members should be invited after creating their own account)
    * Add members to the current cotisation (this should be done automatically)
    * Now every member can connect himself to the contract, approve the contract to spend his funds and make payment to one cotisation
    * The admin should be able to pay the current beneficiary after all members have contributed. When I will insert time management, this will be done automatically
 

