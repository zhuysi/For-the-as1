# How to create Tokens?
   I created a personalized ERC-20 token named &lt;University_name_your_Firstname>, with an initial supply of 2000 tokens. The implementation adheres to ERC-20 standards and includes features to retrieve the latest transaction timestamp, sender and receiver addresses.
As a bonus, I successfully deployed the custom token using Metamask on a testnet blockchain, showcasing practical deployment skills and interoperability.

Usages of this work: 


Token Creation:
After developing the custom ERC-20 token following the specified instructions, deploy the smart contract on a blockchain network.

![image](https://github.com/zhuysi/For-the-as1/assets/119056987/8c5e1334-22d5-4715-bb77-28f16798eb24)


Initial Supply Distribution:
Distribute the initial supply of 2000 tokens among desired addresses or stakeholders according to the project requirements.

![image](https://github.com/zhuysi/For-the-as1/assets/119056987/59b80147-1697-48bd-9f9a-09b4feaee8b7)


Transaction Execution:
Users can initiate transactions by interacting with the smart contract. These transactions involve the transfer of <University_name_your_Firstname> tokens from one address to another.

Transaction Handling:
Users can transfer tokens, and functions allow retrieval of sender/receiver addresses and latest transaction timestamp.
![image](https://github.com/zhuysi/For-the-as1/assets/119056987/a32ce000-c84b-4c3a-8cd2-7b4f4d86d881)

![image](https://github.com/zhuysi/For-the-as1/assets/119056987/6e70b18c-ffa4-47be-834d-0a7df055ba82)

Bonus Task - Metamask Deployment:
Deploy the custom ERC-20 token contract using Metamask on a chosen testnet blockchain (excluding Remix). This step showcases practical deployment skills and compatibility with a real-world testing environment.


Example 1: Token Transfer
		// Assume an instance of the ERC-20 contract named myToken
		
		// Transfer 100 tokens from sender to receiver
		myToken.transfer(receiverAddress, 100);


Example 2: Retrieve Transaction Timestamp
		// Assume an instance of the ERC-20 contract named myToken
		
		// Retrieve the block timestamp of the latest transaction
		uint256 latestTimestamp = myToken.getLatestTransactionTimestamp();


Example 3: Retrieve Transaction Sender Address
		// Assume an instance of the ERC-20 contract named myToken
		
		// Retrieve the address of the transaction sender
		address senderAddress = myToken.getTransactionSenderAddress();


Example 4: Retrieve Transaction Receiver Address
		// Assume an instance of the ERC-20 contract named myToken
		
		// Retrieve the address of the transaction receiver
		address receiverAddress = myToken.getTransactionReceiverAddress();
  ![image](https://github.com/zhuysi/For-the-as1/assets/119056987/0b0c3dfb-3fc7-44a2-9be1-284434d2c719)



