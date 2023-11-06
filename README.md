

![flow](https://github.com/edenite01/Decentralized-Multiplayer-Blockchain-Game/assets/122431567/7a916358-0f03-48c5-b040-1f6493b69c51)

The block diagram explains the project flow of a blockchain multiplayer game.
The overview of the blockchain multiplayer game is as follows, there are two players participating in the blockchain game. The players give a game seed by which a random
number is generated. Then the players make a bet by choosing any number they like.The bet numbers chosen by each player is checked against the random number generated. 
If there is a match between any bet number and random number generated that player is chosen as a winner. If no player has won then the admin who hosted the game is 
chosen as the winner. The winner is displayed.

The flow of the project goes like this, firstly install the npm packages using the command “npm install”. Then run the server using “npm run start”. The browser runs
on localhost:3000 port. The ordinary browser has to be converted into a blockchain browser using Metamask wallet. MetaMask is a cryptocurrency wallet used to interact
with the Ethereum blockchain. MetaMask helps users to access their Ethereum wallet through a browser extension which is used to interact with decentralized application.
The blockchain used is an in-memory blockchain called Ganache. Ganache provides ten fake accounts used for development. To migrate the smart contract truffle package
is used. The command “truffle init” is used to initialize the truffle package. Then the command “truffle migrate –reset” is used to deploy the smart contract to the blockchain.
The UI of the game is displayed using React js which is a frontend framework. The backend used is the Ethereum blockchain which contains the data and the list of
transactions done.
