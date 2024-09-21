# Deploy an ERC-20 Token on ROME Devnet
- Open [Github Codespace](https://github.com/codespaces)
- Faucet [Here](https://romeevm.devnet.romeprotocol.xyz/request_airdrop)
- Paste the below command to Deploy an ERC-20 Token
## 1. Initialize Your NPM Project
```Bash
npm init -y
```
## 2. Install Hardhat & Ethers.js Plugin
```Bash
npm install --save-dev hardhat @nomiclabs/hardhat-ethers ethers @openzeppelin/contracts
```
## 3. Create a HardHat Project
```Bash
npx hardhat init
```
![My Image](https://github.com/ToanBm/hemi-deploy-contract/blob/main/hemi.jpg)
## 4. Add Folder
```Bash
mkdir contracts && mkdir scripts
```
## 5. Write Your Contract
```Bash
nano contracts/MyToken.sol
```
```Bash
