# PayPool Extended Smart Contract

## Purpose
The purpose of this smart contract is to extend the functionalities of the PayPool contract by adding deposit records, managing deposit statuses, and leveraging block timestamps for time-dependent logic.

## Features
- **Deposit Records**: Records the depositor's address, deposited amount, and timestamp for each deposit.
- **Deposit Statuses**: Uses an enum to represent deposit statuses (Pending, Approved, Rejected).
- **Approval and Rejection of Deposits**: Allows the owner to approve or reject deposits.
- **Retrieve Deposit History**: Allows anyone to retrieve the history of deposits.

## How It Works
1. **Deposit Function**: Stores deposit records with timestamps and initializes their status as Pending.
2. **Approval and Rejection**: Owner-only functions to set a deposit's status to Approved or Rejected.
3. **Retrieve Deposit History**: Function to return the depositHistory array.

## Deployment and Testing
The contract is rigorously tested in Remix IDE. It can be deployed on Scroll Sepolia testnet.
