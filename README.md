# Revolutionizing Fintech Hiring: Enabling Instant Cryptocurrency Payments through Ethereum Blockchain Integration 
## Executive Summary:
This project details the integration of the Ethereum blockchain into KryptoJobs2Go, a fictitious startup focused on transforming fintech hiring. The project's goal is to enhance the platform, enabling users to effortlessly find, hire, and instantly pay fintech professionals with cryptocurrency. 
As the lead developer, the primary objective is to seamlessly integrate the Ethereum blockchain network into KryptoJobs2Go, providing customers the capability to make immediate cryptocurrency payments to their hired professionals. The implementation involves importing Ethereum transaction functions, signing and running payment transactions, and inspecting transactions in Ganache.This strategic integration places KryptoJobs2Go at the forefront of innovative solutions in the global gig economy.

## Objectives:
- Integrate Ethereum transaction functions into the KryptoJobs2Go application.
- Sign and run a payment transaction using the Ethereum blockchain.
- Inspect the transaction details in Ganache for validation.

## Methodology:
#### Import Ethereum Transaction Functions:
1. Review and understand crypto_wallet.py code.
  - Add mnemonic seed phrase to SAMPLE.env, rename it to .env.
  - Import functions from crypto_wallet.py to fintech_finder.py: generate_account, get_balance, send_transaction.
  - Create 'account' variable using generate_account in Streamlit sidebar.
  - Display customer account balance with get_balance.

2. Sign and Run a Payment Transaction:
  - Calculate wage in ether based on selected fintech professional's hourly rate and hours worked.
  - Display calculated wage in Streamlit sidebar.

3. Implement code to send Ethereum blockchain transaction to pay hired candidate:
- Use send_transaction with Ethereum account, candidate_address, and wage parameters.
- Save returned transaction hash as 'transaction_hash,' display it in the web interface.

4. Inspect the Transaction in Ganache:
- Navigate to project folder, activate Conda dev environment in the terminal.
- Launch Streamlit application with 'streamlit run fintech_finder.py.'
- Select a candidate, input hours, and click 'Send Transaction.'
- In Ganache, capture screenshots of:
  - Address balance and history.
  - Transaction details.
   - Recipient's address balance and history.

## Technology Used:
- Streamlit library
- Ethereum blockchain
- Ganache

## Final Remarks and Global Implications:
Integrating Ethereum blockchain in KryptoJobs2Go revolutionizes the fintech hiring process by enabling instant and secure cryptocurrency payments. This enhances efficiency, reduces transaction costs, and promotes financial inclusion in the rapidly evolving fintech industry. The transparency and immutability of blockchain contribute to trust and accountability, making KryptoJobs2Go a cutting-edge solution in the global gig economy.

## Deployment Instructions:

1. Ensure the Conda dev environment is active.
2. Launch and create quickstart workspace in Ganache.
3. Run the command 'streamlit run fintech_finder.py' in the terminal.
4. Select a candidate, input hours, and click 'Send Transaction.'
5. Inspect the transaction details in Ganache for validation.

#
#
## Streamlit Application
## Ganache Transactions


