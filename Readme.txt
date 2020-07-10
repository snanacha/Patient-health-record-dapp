This dapp is built with a smart contract that runs the patient health record management. In this  dapp, only patients have the rights to see his/her Records.
Whenever the patient  visits a hospital or halth cenytre and wishes to share his health record and other details, he/she should give his/her public Key which the hospital can enter to access the data. Now, Whenever patient wants to see any Record he will be able to see along with the timestamp. No one except the patient will be able to see the Records. ALso , the patient has to provide his/her public and private key to see the HeathRecords.

How to run this dapp?

step1:
	install geth.
step2:
	Initiate genesis.json with a NodeName.
Step3: 
	Start the node at port 8545. 
step4:
	Create some Accounts with personal.newAccount();
Step5:
	Start the mining by Miner.start().
Step6:
	Open Remix.ethereum.org and copy the Solidity file in IDE. (file location ./Contract/PatientRecord.sol
Step7:
	Go to Run section and select web3 provider.A pop will come. click on OK. 
Step8: 
	Deploy your smartContract and get the ABI and Contract Address. 
Step9:
	Make changes in Server file where ABI and Contract Address is required. 
Step10:
	open the console. type npm Install. It will install all dependencies and then type node server.
step11:
	Go to localhost:3000
Step12:
	Enter the Details and publicKey of Patient. click on Submit.
Step13: 
	Click on "Visit to patient portal"
step14:
	In "Get total Number of Record Section", Patient will enter his public and private Key.
step15:
	In "Get Record", Patient will type the index of record for which he want to see the detail and his public and private key.
