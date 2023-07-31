# Polygon Module 3 
Create a circuit using the circom programming language that implements the following logical gate.

## Description
For this project, you will create a circuit using the circom programming language that implements the following logical gate.

## Steps
1. First clone this project.
2. After cloning , to install the necessary packages write `npm i` in your terminal.
3. Then go to the circom file then for the project make the changes so that we can implement the above logic gate.
4. Configure the hardhat.config.ts so that we can deploy it in the mumbai testnet.
5. You have to add the mumbai public rpc according to your choice and private key.
6. The account you add should have the test matics.
7. If you don't you can get the test matics from this website:https://mumbaifaucet.com/
8. After setting this up, run this command `npx hardhat circom` on your terminal.
9. In order to deploy the contract npx hardhat run scripts/deploy.ts --network mumbai.

## Output
If you followed all the steps correctly you will get a contract address where it is deployed and verifier result: true.

## Authors

Gajula Amulya [21BCS9530@cuchd.in]

## License

This project is licensed under the [GNU General Public License v3.0] License - see the LICENSE file for details.
