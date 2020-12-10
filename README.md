# BMU Vote

**BMU Vote** is blockchain based Electronic Voting System.

# Work Flow

## Voters
- Fills the **Voter Form**.
- Admin verifies the voter based on his data.
- Can view all Candidate Details.
- After voting starts, voter can voter for a candidate of their constituency.

## Admin
- Adds **Candidate Details**.
- Verifies voter based on their details.
- Can *start* and *end* election.
- Seek **results** of election.
- 
 ### Prerequisites
```
Node.js 
Truffle
Metamask or ganache-cli
```

### Installing
Clone the repository
```
git clone https://github.com/MayankPunghal/BMU_Vote.git
```
Change directory to /CoreProject
```
cd CoreProject
```
Install dependencies
```
npm install
```
Check if truffle is installed properly
```
truffle version
```
Compile all the contracts
```
truffle compile --all
```
- Make migrations for the contract ( ganache-cli )
```
truffle migrate --reset
```
- Make migrations for the contract ( Metamask )
```
truffle migrate --reset rinkeyby
```
Change directory to /client
```
cd client
```
Install dependencies
```
npm install
```
Run the server
```
npm start
```
## Authors
- **Mayank, Shikhar and Harshil**

