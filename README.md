# Table of Contents 
* 1 . Simple Lottery
* 2 . Recurring Lottery
* 3 . RNG Lottery
* 4 . Powerball
* 5 . Ethereum
  * 5.1 Simple Lottery
  * 5.2 Recurring Lottery
  * 5.3 RNG Lottery
  * 5.4 Powerball
 * 6 . Hyperledger
   * 6.1 Simple Lottery
   * 6.2 Recurring Lottery
   * 6.3 RNG Lottery
   * 6.4 Powerball

## 1. Simple Lottery
   Simple Lottery works by picking one player or participants who bought a lottery ticket. Players can buy one ticket per transaction. Player dont need to bet on any number.
## 2. Recurring Lottery
  This Recurring Lottery occurs every rounds so that a new prize is started everytime the old one closed.
The users can purchase not only one ticket but multiple tickets in a one transacion and they can add some security improvements.
Chat Conversation End
Type a message...
## 3. RNG Lottery
  The RNG lottery will occur in rounds so that a new prize pool is started every
time the old one closes. It will also allow users to purchase multiple
tickets in one transaction instead of just one and add a couple of security
improvements.
## 4. Powerball
  Powerball is the most popular type of lottery played in the United States.
In this section, we are going to write a contract that ports this game onto
Ethereum.
In Powerball, the user picks six numbers per ticket. The first five
numbers are standard numbers from 1–69, and the sixth number is a
special Powerball number from 1–26 that offers extra rewards. Every three
or four days, a drawing is held, and a winning ticket consisting of five
standard numbers and a Powerball number is picked. Prizes are paid out
based on the number of winning numbers matched on your ticket.
## 5. Ethereum 
##### 5.1 Simple Lottery ( Ethereum )
   Start the smart contract by adding any number in duration, Once it started or deployed anyone can buy a lottery ticket. After the duration the smart contract can draw the winner among the participants.
##### 5.2 Recurring Lottery ( Ethereum )
   Starting of the contract, the deployer will execute a contract, then the deployer will specify the duration of the round. after the duration, it will pick a winner, the deployer has an option to check each round winner and delete a round if needed. 
##### 5.3 RNG Lottery ( Ethereum )
   In RNG Lottery, the user should register first their address and a secret number known only to the user. This secret number and address will generate a commitment hash, this hash is needed in order to buy a ticket (1 ticket only). There is a deadline in  buying ticket for the lottery, after the period is over, all players must show their secret number during reveal period if not they will be automatically dropped in the list of participants. When reveal period is over an admin will draw a random pick in the lottery that will declare the winner and receive the ether prize.
##### 5.4 Powerball ( Ethereum )
  For the Ethereum platform there's additional process in technical part. The deployer will deploy the smartcontract and deploy itself as Admin. Second, There is an approval came from the Orderer and the Ordere will deploy the smartcontract. The Player must register first before entering the game. The game will start after those technical part is done. The User will check the Max number and Max number of Powerball before buying a ticket and the Ticket worth 0.02 ether. The account who deployed the smartcontract will draw the number 1-69 on 5th no. and number 1-26 on last no.The Player can check the winning combination after the draw. The Winner can withdraw the jackpot. Prizes are based on the on the winning numbers matched on the ticket.
   


