# AidSafe

Decentralized donor governance platform for humanitarian aid using XRP Ledger escrow with community-driven fund release voting.

## 📂 GitHub Repositories

**Frontend Application**: [https://github.com/tyhh00/charity-xrp-frontend](https://github.com/tyhh00/charity-xrp-frontend)
*React-based donor dashboard and voting interface hosted on Cloudflare Pages*

**Backend API**: [https://github.com/tyhh00/xrp-charity-backend](https://github.com/tyhh00/xrp-charity-backend)
*Node.js API server for proposal management and XRPL integration hosted on Cloudflare Workers*

**Python Backend**: [https://github.com/tyhh00/python-charity-xrp](https://github.com/tyhh00/python-charity-xrp)
*Python Backend for XRPL integration*

## 💻 Live Website:
[Live Safeaid Website](https://charity-xrp-frontend.pages.dev/)

## 📸 Screenshots

### Platform Overview
![AidSafe Dashboard](https://github.com/tyhh00/SafeAid/blob/main/Screenshots/Screenshot%20(18).png?raw=true)
*Main landing page*

### Donation Page
![Donation Flow](https://github.com/tyhh00/SafeAid/blob/main/Screenshots/Screenshot%20(19).png?raw=true)
*Main donor dashboard showing active proposals and donation history*

### Donation Modal
![Donation Flow](https://github.com/tyhh00/SafeAid/blob/main/Screenshots/Screenshot%20(20).png?raw=true)
*Step-by-step donation process with XRPL integration*

### Proposal Voting
![Voting Interface](https://github.com/tyhh00/SafeAid/blob/main/Screenshots/Screenshot%20(21).png?raw=true)
*Community voting system*

### Proposal Voting Modal
![Escrow Transaction](https://github.com/tyhh00/SafeAid/blob/main/Screenshots/Screenshot%20(22).png?raw=true)
*Community voting interface for proposal approval*

## 🎥 Demo Video (30 seconds)

[Demo Video Link](https://www.youtube.com/watch?v=cN44o2XYf-c&feature=youtu.be)

*[Replace with your 30-second demo video showing donation process, proposal creation, and voting workflow]*

## 🔗 XRP Ledger Integration

### How It Works

Our donor governance system leverages XRP Ledger's escrow functionality for transparent, community-controlled aid distribution:

1. **Donor Contributions**: Donors send RLUSD/XRP to charity escrow wallets, funds are immediately locked on-chain
2. **Proposal Creation**: NGOs create detailed funding proposals (e.g., "$100k for emergency medical supplies in Region X")
3. **Community Voting**: Donors vote yes/no on proposals using their wallet signatures, weighted by contribution amount
4. **Automated Release**: When proposals reach majority approval threshold, escrow funds are automatically released to designated vendors/recipients
5. **Transparency Tracking**: All donations, votes, and fund releases are publicly recorded on XRP Ledger

### Key XRPL Features Used

- **RLUSD Donations**: Donors contribute to charities using RLUSD
- **Charity Escrow**: Funds locked until community consensus is reached
- **RLUSD Stablecoin**: Stable value donations for predictable aid budgets
- **Fast Settlement**: 3-4 second voting confirmation and fund release
- **Low Costs**: Sub-penny transaction fees enable micro-donations and frequent voting

### Donation & Voting Flow

```
Donor → Escrow Wallet → Proposal Created → Community Vote → Funds Released
  ↓         ↓              ↓               ↓              ↓
RLUSD    Locked        "$100k for        Yes/No        Vendor
Sent     On-Chain      Medical Aid"      Voting        Payment
```

## 🔍 XRPL Testnet Transactions

**Live transaction examples on XRP Ledger Testnet:**

- **Donor Contribution**: [https://blockexplorer.one/xrp/testnet/address/rnGr2JNKaqCKdjeKV5jskA9pMoPJrn1JXJ](https://blockexplorer.one/xrp/testnet/address/rnGr2JNKaqCKdjeKV5jskA9pMoPJrn1JXJ)
- The blob is created, but the transaction hash itself cant be found on chain

*All transactions demonstrate real RLUSD escrow functionality and community governance*

## 🗳️ Governance Model

### Proposal Types
- **Emergency Relief**: Immediate disaster response funding
- **Long-term Projects**: Infrastructure and development initiatives  
- **Operational Costs**: NGO administrative and operational expenses
- **Equipment Purchases**: Medical supplies, food, shelter materials

### Voting Mechanics
- **Weighted Voting**: Vote power proportional to donation amount
- **Quorum Requirements**: Minimum participation threshold for valid votes
- **Approval Threshold**: Majority consensus required for fund release
- **Time Limits**: Proposals expire after set voting period

### Example Proposal
```
Title: "Emergency Medical Supplies - Haiti Earthquake Response"
Amount: $100,000 RLUSD
Purpose: Purchase and distribute medical supplies to earthquake victims
Vendor: Verified medical supply distributor (Wallet: rVendor123...)
Timeline: 72 hours for delivery
Voting Period: 48 hours
Current Status: 67% approval (Threshold: 51%)
```
