# SnawSwap


**SnawSwap is a decentralized crypto-to-fiat swapping platform built on the Solana blockchain that enables users to swap tokens (e.g., USDT, USDC, SOL) for Nigerian Naira (₦) directly into their bank accounts via a secure and non-custodial system.**<br>


##  Key Features

-  Fast and Low-Cost Swaps – Powered by Solana blockchain.
-  Non-Custodial – Users retain control of their assets.

-  Token to Naira Swap – USDT, USDC, or SOL  to ₦.

-  Direct Bank Payouts – Funds go straight into Nigerian bank accounts.

-  P2P Liquidity Network – Matched with real users or liquidity partners.

-  Transparent History – Users can view transaction history securely<br>


#  Getting Started

## 1. Clone the repository

```
git clone https://github.com/your-username/snawswap.git
cd snawswap
```

## 3. Frontend Setup (Tailwind)

```js
cd frontend
npm install
npx tailwindcss -i ./input.css -o ./css/style.css --watch
```
### Open ``frontend/index.html`` in your browser to preview the UI.


##  Tech Stack

- #### Frontend: HTML, Tailwind CSS

- #### Blockchain: Solana, Solana Web3.js, Phantom Wallet

- #### Payments: P2P or third-party APIs for NGN disbursement


## Works How It

1. User connects wallet and selects token to swap.

2. System calculates live conversion rate.
3. Upon confirmation, user sends token to a smart escrow.

4. NGN equivalent is transferred to their bank account via liquidity partner.
5. All operations logged securely.

##  Scalability

- The system supports adding more fiat currencies.

- Can onboard external liquidity providers.

- Optional KYC integration for regulatory compliance.

##  Development Mode

```rust
solana config set --url https://api.devnet.solana.com
```

##  Contributing
### ***Pull requests are welcome. For major changes, please open an issue first.***

##  License
This project is licensed under the MIT License.

##  Author

**Faruk Idris**.

Building for Colessum Hackathon 2025 

Follow the journey on [Twitter](https://x.com/farukidris_)

#SnawSwap 

