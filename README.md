# Basic Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, a sample script that deploys that contract, and an example of a task implementation, which simply lists the available accounts.

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```
# Create hardhat project

mkdir hardhat-project
cd hardhat-project
npm init --yes
npm install --save-dev hardhat

# Deploy to local node
https://hardhat.org/guides/deploying.html

npx hardhat node
npx hardhat run --network localhost scripts/sample-scripts.js