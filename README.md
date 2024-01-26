Overview

The AITU_Token is an ERC-20 token specifically designed for representing university-related assets on the Ethereum blockchain. It builds upon the OpenZeppelin ERC-20 implementation while introducing custom functionalities, notably the tracking of transaction timestamps and receiver addresses.

Features

ERC-20 Standard Compliance: AITU_Token adheres to the ERC-20 standard, ensuring compatibility and interoperability within the Ethereum ecosystem.

Transaction Timestamp Tracking: The token includes the ability to track transaction timestamps, providing insight into the timing of transactions in a human-readable format.

Sender and Receiver Address Retrieval: AITU_Token enables users to retrieve the Ethereum addresses of both the transaction sender and receiver, enhancing transparency and record-keeping.

Usage

To utilize AITU_Token, deploy it on the Ethereum blockchain using tools like Remix or Truffle, along with an Ethereum wallet such as Metamask.

Functions

image

getLastTransactionTimestamp

Description: Returns the timestamp of the latest transaction block in a human-readable format. Usage: Call this function to obtain the timestamp of the most recent transaction.

image

getTransactionSender

Description: Retrieves the address of the transaction sender. Usage: Employ this function to acquire the Ethereum address of the sender in the latest transaction.

image

getTransactionReceiver

Description: Retrieves the address of the transaction receiver. Usage: This function returns the Ethereum address of the receiver in the second-to-last transaction.
