##PROPOSAL TO ENACT A COMMITTIE OF PIRATES, PROGRAMMERS, AND ANARCHISTS##
#Executive Summary#
The purpose of this document will be to establish a collective voting committee on the EthereumClassic block chain for the purpose of collective management of funds contributed to the development team. This documentation and accompanying smart contract will be intentionally limited in scope and specifically address financial management of the development team needs. Under no circumstance will this document be used as a basis for governance of the EthereumClassic platform.   
#Statement of Need#
Being that interested parties would like to contribute to the development of the EthereumClassic  platform; and being that the development team ideologically believes the platform should remain as a decentralized, censorship-resistant platform;  it is necessary for a collective voting system to be established to allow for public auditing of the funds contributed while enabling the development team the ability to cover cost that may arise in the course of platform maintenance, development, and improvement without being beholden to a central foundation.  

#Definitions# 

Contributor – any party freely sending funds to the smart contract to be distributed as the committee decides 
Evaluation – Measures of result and effectiveness
Party – a person, organization, smart contract, or any similarly situated representative capable of meeting the cryptographic verifications put forth in this document; without any limitation implied due to age, gender, race, nationality or religion  
Proposer – any party presenting a proposal
President – the owner of the contract
Voting member – any party who has been elected to the committee by the committee 

#Objectives#
1) Create a smart contract on the EthereumClassic chain which allows for members to:
-	Vote on financial and budgetary decisions
-	Elect new members to the committee
-	Remove members from the committee
-	Send funds to wallets based on vote outcome
-	Elect the president of the committee 
-	Dissolve

2) Establish a public forum for proposals which is to be available in perpetuity which will:
-       identify by Public key signature the party issuing the proposal
-       The amount of ether requested
-       A statement of need, objective, methods, and evaluations of the project
-       expected future funding needs
-       Voting date

3) Establish a method for validating present value of a contribution

#Method#

<i>Initial State</i>
A repository will be established in the github.com/ethereumproject/ namespace which will be used for this document as well as future contracts. 
All current members of the development team will vote for a president and the president will issue the smart contract.
All voting members will be given both the contract address and the interface file and verify it has been established as intended 

<i>Operations</i>
Upon receiving a matter to vote on all members will be notified and allowed 48 hrs. from the time a proposal is presented to review the issue. 
The president will propose a distribution of coins to the committee. 
The voting members will then vote on whether to accept this distribution. 
In case of a tie vote, the president has the deciding vote. 
The minimum quorum for proposals to be voted on will be three quarters of the voting body.
Margin of votes for majority will be a simple majority; 51% of the quorum.
At the conclusion of the vote the coins either will or will not be distributed to the proposer and public notice will be made.
If the vote is not to fund the proposal will not be voted on again until all other proposals are voted on or 2 weeks; whichever is longer.

<i>Fund present value</i> 
Coins are distributed based on the first in first out (FIFO) principle. 
As a contribution is made to the contract it not be spent until all coins that were in the contract before it are spent.
A public ledger of funds contributed will be maintained for transparency.
Example:  
•	The contract has 0 ether. 
•	Alice contributes 10 ether. 
•	Bob contributes 20 ether.
•	Chloe contributes 10 ether.
•	The fund now has 40 ether.
•	Paul the proposer requests, and is granted, 15 ether.
•	The fund now has 25 ether remaining. (0 from Alice, 15 from Bob, 10 from Chloe)
•	If a vote to dissolve were passed; Alice would be refunded 0 ether, Bob would be refunded 15 ether, and Chloe refunded 10.   
#Vote to Dissolve#
The committee can be dissolved at any point by issuing a vote in the forum. 
If the vote to dissolve is passed; all funds remaining in the contract will be automatically refunded to the original contributors based on the FIFO method detailed above.  

#Hard Rules#
A proposal to dissolve shall automatically be issued and voted on every 6 months in order to maintain public trust.
A proposal to change president shall automatically be issued and voted on every 13 months. A president will serve a maximum of 3 consecutive terms.   
NO VOTING MEMBER SHALL MAKE ANY PROPOSAL WHICH DIRECTLY BENIFETS THEMSELVES OR ANY OTHE MEMBER; to the exclusion of being paid for work directly related to the project. 
Example: 
Member Alice shall not propose to send Member Bob 500 ether to have member Bob’s car washed. 
Member Alice could propose to send Member Bob 200 ether a week for website design.
NO VOTING MEMBER SHALL VOTE ON ANY PROPOSAL FROM WHICH THEY BENIFET UNLESS A QUARUM CANNOT BE OTHERWISE MET

#Three Documents#
All voting members of the committee will cryptographically sign this document, the final version of the smart contract, and a record of these signature will be stored in the repository established above.  

