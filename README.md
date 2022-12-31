# Full Stack Blockchain App

This is my first experience dealing with blockchain on a low level, I made a full stack Blockchain application, using JavaScript primarily 
the app is based on  [Udemy Course](https://www.udemy.com/course/build-blockchain-full-stack/) 

# What has been made
The full project made based on the course is about creating a blockchain application from scratch, it uses JavaScript as its main language and make files for blocks, blockchain, wallet, transactions, and then test the files with Jest testing framework.
we also had a basic experience with dealing with Redis and used particularly the pub/sub architecture model in it.

## Testing the files

Because the blockchain code particularly the smart contact can not be changed once deployed,, it must be tested before deployment, that is why it was used the Test driven development approach, where we make our requirements and then make the code that satisfy the requirements made in the tests, so we used Jest.

## Blocks

First, we had an interaction with what a block consists of, and we implemented it using JavaScript, it had nonce, hash function, and reference block or the genesis block, timestamp, and the difficulty.

## Blockchain

Second, we made the blockchain class which encapsulates the blocks in it to form the blockchain, it contains functions like adding the block to the chain, validating the transactions, and replacing the chain with another chain according to the proof of work concept.

## Encryption

Third we made the hash class to define the hash function, which we used SHA256 in it, which is the standard for security. We were thinking about the difficulty for mining, and we first made it and then returned the hashed to hex value.

## Wallet
Forth, we created a wallet for sending and receiving transactions by providing parameters like sender and receiver address and the amount sent and functions like creating the transactions , signing them, and calculating the balance etc.…

## Mining transactions

I made a mining transactions class that make miners do work that requires a GPU for mining a transaction and receiving a token and that makes the network secure from attacks and trustable.

## Pub/ sub using Redis

Redis Pub/Sub : implements the messaging system where the senders (in Redis terminology called publishers) sends the messages while the receivers (subscribers) receive them.
I used it for the project so that we can utilize the power of message synchronization, which will help to mining the transactions



##  Front-end

For the front end: I used ReactJs.
