# 🌟 StellarAid-api
StellarAid Backend is the server-side API powering the StellarAid crowdfunding platform — a blockchain‑enabled system built on the Stellar network to support transparent, secure, and efficient fundraising for social impact initiatives.

3 Folder structure
```
/src
  /modules
    /auth
    /users
    /projects
    /donations
    /wallet
    /admin
    /notifications
  /common
  /database
  /config
```
# 📌 Features
### 🎯 For Donors
Discover global fundraising campaigns
Donate in XLM or Stellar assets
Wallet integration (Freighter, Albedo, Lobstr)
On-chain transparency: verify all transactions
### 🎯 For Creators
Create social impact projects
Accept multi-asset contributions
Real-time donation tracking
Withdraw funds directly on-chain
### 🎯 For Admins
Campaign approval workflow
User & KYC management
Analytics dashboard
# 🏗️ Architecture Overview
StellarAid Backend is built with:

- NestJS
- PostgreSQL
- Prisma ORM
- Horizon API integration
- Worker processes (BullMQ)
# 📌 How to Contribute
### 1. Fork the Repository
Click the “Fork” button in the top‑right of the GitHub repo and clone your fork:
```
git clone https://github.com/YOUR_USERNAME/stellaraid-api.git
```
cd stellaraid-api

### 2. Create a Branch
```
git checkout -b feature/add-donation-flow
```
### 3. Commit Messages
Use conventional commits:

- feat: add wallet connection endpoint
- fix: resolve donation API error
- docs: update project README
- refactor: clean up project creation form
### 4. Submitting a Pull Request (PR)
Push your branch:
```
git push origin feature/add-donation-flow
```
Open a Pull Request from your fork back to the main branch.

# 📜 License
MIT License — free to use, modify, and distribute.
