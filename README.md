# Proveably Random Raffle Contracts

## About

This code is to create a proveably random smart contract lottery.

## What we want it to do?

1. Users can enter by paying for the ticket.
    1. The ticket fees are going to go to the winner after the draw.
2. After x period of time, the smart contract lotter will draw a winner.
   1. And this will be done programatically.
3. We are going to be using Chainlink VRF and Chainlink Automation.
   1. Chainlink VRF -> Randomness
   2. Chainlink automation -> Time based trigger

## Tests

1. Write some deploy scripts
2. Write our tests
   1. Work on a local chain
   2. Forked Testnet
   3. Forked Mainnet
