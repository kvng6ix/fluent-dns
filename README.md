# 🎨 Fluent DNS - Decentralized Domain Name Service

A modern, decentralized domain name service built on the Fluent Network testnet. Register and manage blockchain-based domains with dynamic pricing and real-time statistics.

![Fluent DNS](https://img.shields.io/badge/Network-Fluent%20Testnet-8b5cf6)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Live-success)

## 🌟 Features

- **🔒 Decentralized Ownership**: Domains stored on blockchain, no central authority
- **💎 Dynamic Pricing**: Fair pricing based on domain length (0.01/0.005/0.001 ETH)
- **📊 Live Statistics**: Real-time data showing total domains and ETH locked
- **🔍 Domain Lookup**: Check ownership and target addresses of any domain
- **⚡ Multi-Wallet Support**: Works with MetaMask and other Web3 wallets
- **📱 Responsive Design**: Beautiful interface that works on all devices
- **🔄 Transferable**: Transfer domain ownership to other addresses

## 🚀 Live Demo

Visit the live application: [Your Vercel URL Here]

## 📋 Smart Contract Details

- **Contract Address**: `0xF273cd4154D56d50FF32b09A224Cdc2F269b3acA`
- **Network**: Fluent Testnet (Chain ID: 20994)
- **Block Explorer**: [View on Fluent Scan](https://testnet.fluentscan.xyz/address/0xF273cd4154D56d50FF32b09A224Cdc2F269b3acA)

## 💰 Pricing Structure

| Tier | Length | Price |
|------|--------|-------|
| 🏆 Premium | 1-5 characters | 0.01 ETH |
| ⭐ Standard | 6-10 characters | 0.005 ETH |
| 💚 Economy | 11+ characters | 0.001 ETH |

## 🛠️ Technology Stack

- **Frontend**: Vanilla HTML5, CSS3, JavaScript
- **Web3**: Ethers.js v6
- **Blockchain**: Fluent Network (Ethereum-compatible)
- **Deployment**: Vercel
- **Smart Contract**: Solidity ^0.8.24

## 🔧 Network Configuration

To use Fluent DNS, add the Fluent Testnet to your wallet:

```
Network Name: Fluent Testnet
Chain ID: 20994
RPC URL: https://rpc.testnet.fluent.xyz/
Currency Symbol: ETH
Block Explorer: https://testnet.fluentscan.xyz/
```

## 🎯 Getting Testnet ETH

Get free testnet ETH from the [Fluent Faucet](https://testnet.gblend.xyz/)

## 📦 Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/fluent-dns.git
   cd fluent-dns
   ```

2. **Open in browser**
   Simply open `index.html` in your browser or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```

3. **Connect wallet and start using!**

## 📁 Project Structure

```
fluent-dns/
├── index.html          # Main application file
├── README.md           # This file
├── LICENSE             # MIT License
├── package.json        # Node.js dependencies (for deployment)
├── vercel.json         # Vercel deployment configuration
└── .gitignore          # Git ignore rules
```

## 🚀 Deployment

### Deploy to Vercel

1. **Fork this repository**
2. **Connect to Vercel**
3. **Deploy with default settings**
4. **Your dApp is live!**

### Deploy to Netlify

1. **Fork this repository**
2. **Connect to Netlify**
3. **Build settings**: None needed (static site)
4. **Deploy**

## 📝 Smart Contract Functions

- `register(name, target)` - Register a new domain
- `available(name)` - Check if domain is available
- `ownerOf(name)` - Get domain owner
- `resolve(name)` - Get domain target address
- `transferName(name, newOwner)` - Transfer domain ownership
- `setAddress(name, target)` - Update domain target
- `getPrice(name)` - Get registration price

## 🔐 Security

- All transactions are secured by the Fluent Network
- Smart contract is immutable and audited
- No private keys are stored or transmitted
- All interactions happen client-side

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Fluent Network](https://x.com/fluentxyz) for the amazing blockchain infrastructure
- [Ethers.js](https://ethers.org/) for the Web3 library
- The Fluent community for support and feedback

## 📞 Support

If you have any questions or need help:

- Open an issue on GitHub
- Follow [@fluentxyz](https://x.com/fluentxyz) for updates
- Made with ❤️ by [0xbito](https://x.com/kvng6ixx)

---

**⚡ Powered by Fluent Network | 🎨 Built by top gooner 0xbito**