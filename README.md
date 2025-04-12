# Event-Ticket-Registration-System
A decentralized event ticketing system using Solidity and NFTs (ERC-721). Tickets are minted as NFTs and metadata is stored on IPFS via Pinata. Ensures secure, verifiable, and fraud-proof ticket ownership and transfers on the Ethereum blockchain.



# 🎫 Event Ticket Registration System (Blockchain + NFT)

A decentralized event ticketing system built on the Ethereum blockchain using **Solidity**. Tickets are minted as **ERC-721 NFTs**, with metadata stored on **IPFS via Pinata**, ensuring secure, verifiable, and fraud-resistant ticketing.


 🚀 Features

- 🎟️ Mint event tickets as NFTs (ERC-721)
- 🔐 Secure, transparent ticket ownership
- 📦 IPFS metadata storage using Pinata
- 🔄 Transferable and verifiable tickets
- 🚫 Prevents fraud, duplication, and scalping



 🛠️ Tech Stack

- **Solidity** – Smart contracts
- **Ethereum** – Blockchain platform
- **Pinata** – IPFS-based file storage
- **Remix IDE** – For development and deployment
- **Metamask** – Wallet for user interaction


 📂 Project Structure


contracts/
  └── TicketNFT.sol       # Smart contract for minting & managing NFT tickets
metadata/
  └── event.json          # Event and ticket metadata (uploaded to Pinata)
scripts/
  └── uploadToPinata.js   # Node script to upload metadata to IPFS via Pinata





1. Organizer deploys the smart contract.
2. Event metadata is uploaded to IPFS using Pinata.
3. Tickets are minted as NFTs with metadata URI.
4. Users receive tickets directly to their wallet (e.g., MetaMask).
5. Ownership is recorded on-chain and can be verified by anyone.

---

Installation & Deployment

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/event-ticket-nft.git
   cd event-ticket-nft
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Add your Pinata API keys in a `.env` file:
   ```
   PINATA_API_KEY=your_api_key
   PINATA_SECRET_API_KEY=your_secret
   ```

4. Upload metadata to IPFS:
   bash
   node scripts/uploadToPinata.js
   

5. Deploy the smart contract via Remix or Hardhat.


 📄 License

This project is licensed under the MIT License.



 🙌 Acknowledgements

- [Ethereum](https://ethereum.org)
- [Pinata](https://pinata.cloud/)




