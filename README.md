# Oracle-Network
Interaction with oracle networks (chainlink) . <br>
As we know that Blockchain offers security and decentralization, among other benefits.There are, however, some limitations to the blockchain. Due to their inherently closed nature, these systems have fewer inputs than open systems, which is good for security and integrity but also limits their ability to accept data. It is, therefore, necessary to build a sort of bridge between these systems and the rest of the world to see what is going on .<br>
The input cannot occur from a single source if the system is yet to function. why? This would contradict the very spirit of blockchain since it would rely on one central source for data. ***Chainlink*** can be very useful in solving this problem. <br>
Here , a project is made which shows how a smart contract can ask for some real world data . There is caller smart contract which is a user smart contract which asks for the real world data from chainlinks. 
<br>
An ***oracle*** is software known as 'middleware' that acts as an intermediary, translating data from the real world to smart contracts on the blockchain and back again.
However, a single centralized oracle creates the very problem a decentralized, blockchain-secured smart contract aims to solve — a central point of weakness.
So we are going to make multiple source of real world data . <br>
After collecting data from different oracles the smart contract then decide and sends the original data to caller smart contract.
