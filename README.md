# Crowd Funding Smart Contract

This project creates a smart contract that powers a crowdfunding platform where users can seamlessly and securely fund interesting campaigns of value.


##### Project Functionalities

- Users can create new campaigns.
- Beneficiary of the campaign can withdraw funds in the campaign
- Users can make donation for specific campaings
- Campaigns can end according to deadline.
- Owner of the smart contract can withdraw remaining funds for contract that have been ended


```
Ensure to create .env file with the following environment variables

PRIVATE_KEY=KEY
ALCHEMY_API=KEY
ETHERSCAN_API_KEY=KEY
ALCHEMY_API_KEY=KEY
```

##### Improvements

- Optimize operations for retreiving users by using mapping instead of loops
- Perform security audits to avoid vulnerabilities

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat ignition deploy ./ignition/modules/Lock.js
```
