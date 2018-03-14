
# Bike Share

Bike share is a collection of smart contracts to facilitate the creation of a bicycle sharing dapp.


## Requirements

In this application, a user can rent a bike for an alloted amount of time using a credits.

When renting his bike, a user needs to put up 3 times his credits as escrow, and will get it back when he returns the bike.

A user should be able to purchase credits using Ether at a rate of 1 ETH = 31415.9 BIKE credits

The smart contract should be controlled by the creator

## Bonus points

- Implement unit tests using either Solidity or Javascript

- Add a "transfer rented bike", "transfer credit" functionnality

- If the user does not return his bike after a certain amount of time, his escrowed credits should be slashed

- Remove the credit functionnality from whithin the Bike.sol contract and move it to its own Token Contract

- Dazzle us!

If you have any questions, please email `patrick@vanbex.com`