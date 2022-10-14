# .github
Smart contracts for Nifty Row Protocol
Consists of:
•	Yasuke: responsible for mint, auctions, bids, buy-now etc.
•	Storage: Used for storing about auctions, fees and administrative functions
•	AssetManagerV2:  ArtExchange/Fractional investment functions based on ERC20 for NFTs
•	PhysicalArt: Planned outright purchase function of physical art with credit card payment support


Nifty Row Smart Contracts deployed instances across Mainnet and Testnet:

Yasuke
https://polygonscan.com/address/0xC26A71E42fBFFe46e5450a2e4C5FFE5067f69b9b#code

Storage
https://polygonscan.com/address/0xdabc0b39b43d0ad4fe55dc4adaee5aa911486d35#code

AssetManagerV2
https://goerli.etherscan.io/address/0x8bE90A042c094591f07BA8b4AfB17B6f31C25147#code


Compile, Test, Deploy

Deploy and Verify on Etherscan

yarn install
yarn run deploy --network goerli
yarn run verify --network goerli "AssetManagerV2 contract address"
Protocol Description
Nifty Row protocol is a combination of smart-contracts for creating, auction, sales, trading Non Fungible Tokens representing assets like Arts, Music, Movies and more. 
Steps for minting/creating NFTs.

To mint a user must perform the following basic actions:
1.	Connect metamask/Web3.0 Wallet to the marketplace via connect-button
2.	Click on MINT at the top
3.	The mint page will open
4.	Click on browse and add the File of your choice [IMAGE,MUSIC,VIDEO]
5.	Select the category of the art below
6.	Input data in required data fields for the NFT
7.	Click Create Art
8.	Confirm the transaction via metamask/web3.0 wallet

Steps for starting an English Auction:
1.	Connect metamask/Web3.0 Wallet to the marketplace via connect-button
2.	In order to start an auction a user must perform the following
3.	Navigate to the profile page and select an NFT to reveal its details
4.	Specify the start and end dates for the auction
5.	Specify the minimum-bid for the auction
6.	Specify the sell-now price for the auction
7.	Click start-auction button
8.	Confirm transaction via Metamask/Web3.0 wallet

License

The Nifty Row protocol contracts are available under the MIT License.
