# blockchain-voting

## idea for codefundo++: Team stormborn

### What we are planning to build

- Use Azure Blockchain to expedite counting and tallying of votes. 
- Empower the citizens residing in any location to vote online securely.
- Vote verification: Voters can ensure that their votes are securely registered

### How it works

We use three blockchains - one for the Voter Registration, Voting and Candidates. Every new voter, whenever he/she registers is added to the Voter Registration chain. Each voter is added as a new block to the chain which is verified by a government  verified miner. On the voting day, when a voter wants to vote, he/she will be verified by checking the Voter Registration chain. Once verified, the vote is recorded to the Voting chain. The voter details are not stored on the Voting chain but rather a hash is stored along with the vote. If the voter wants to verify their vote, they can input their identification details which will internally be verified against the hash.

### Datasets to be used

We will create our own dataset for the project ensuring that all the basic required details like Full Name, Age, Nationality, Country of Residence, Voter ID are present in the dataset.

### Technologies used
- Ethereum 
- Azure Blockchain
- Ganache
- Truffle
