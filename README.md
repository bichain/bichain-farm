# 🌾 Bichain Farm

A blockchain-based farming game built on **ApeChain** with **ENS** integration and persistent storage.

![Game Preview](https://img.shields.io/badge/Status-Live-success)
![ApeChain](https://img.shields.io/badge/Network-ApeChain-orange)
![ENS](https://img.shields.io/badge/ENS-Supported-blue)

## 🎮 Play Now

**Live Demo:** [https://bichain.github.io/bichain-farm/](https://bichain.github.io/bichain-farm/)

## 🌟 Features

- 🌱 **Plant & Harvest Crops** - Grow wheat, carrots, corn, and tomatoes
- 💰 **Earn Money** - Sell your harvested crops for profit
- 🔗 **ApeChain Integration** - Built on ApeChain blockchain
- 🌐 **ENS Support** - Display your ENS domain (.eth) instead of wallet address
- 💾 **Auto-Save Progress** - Your farm progress is automatically saved
- 🌍 **Multilingual** - Available in English, Portuguese, and Spanish
- 📱 **Responsive Design** - Play on desktop or mobile

## 🚀 How to Play

1. **Connect Wallet** - Click "Connect MetaMask" (ApeChain will be configured automatically)
2. **Buy Seeds** - Select seeds from the shop (costs $10-25)
3. **Plant Crops** - Click empty plots to plant your selected seeds
4. **Wait & Grow** - Watch your crops grow in real-time (5-30 minutes)
5. **Harvest & Profit** - Click ready crops to harvest and earn money!

## 🛠️ Tech Stack

- **Frontend**: React 18, Tailwind CSS
- **Blockchain**: ApeChain (EVM-compatible)
- **Web3**: MetaMask Integration
- **Storage**: Persistent browser storage API
- **ENS**: Ethereum Name Service integration
- **Icons**: Lucide React

## 📋 Game Mechanics

### Crops
| Crop | Cost | Sell Price | Grow Time | Profit |
|------|------|------------|-----------|--------|
| 🌾 Wheat | $10 | $12 | 5 min | $2 |
| 🥕 Carrot | $15 | $18 | 10 min | $3 |
| 🌽 Corn | $20 | $24 | 20 min | $4 |
| 🍅 Tomato | $25 | $30 | 30 min | $5 |

### Starting Resources
- **Initial Money**: $50
- **Farm Plots**: 3 plots available

## 🔧 Installation & Deployment

### Prerequisites
- MetaMask browser extension
- Git installed (optional)

### Deploy to GitHub Pages

1. **Fork or Clone this repository**
```bash
git clone https://github.com/bichain/bichain-farm.git
cd bichain-farm
```

2. **Enable GitHub Pages**
   - Go to repository **Settings** → **Pages**
   - Select branch: **main**
   - Click **Save**

3. **Access your game**
   - Your game will be live at: `https://bichain.github.io/bichain-farm/`

### Local Development

Simply open `index.html` in your browser. No build process required!

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server

# Then open http://localhost:8000
```

## 🌐 ENS Integration

The game automatically detects and displays your ENS domain name if you have one registered:

- Resolves ENS names using the ENS API
- Displays your `.eth` domain prominently
- Falls back to wallet address if no ENS name found
- Works with any ENS-compatible domain

## 🔐 Security & Privacy

- **No backend required** - Fully client-side application
- **No API keys** - Direct blockchain interaction via MetaMask
- **Progress saved locally** - Your game data is stored in your browser
- **Non-custodial** - You maintain full control of your wallet

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Ideas for Contributions
- [ ] Add more crop varieties
- [ ] Implement fertilizer system
- [ ] Add achievements/badges
- [ ] Create leaderboard
- [ ] Add sound effects
- [ ] Weather system
- [ ] Multiplayer features

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with ❤️ for the blockchain gaming community
- Powered by [ApeChain](https://apechain.com)
- ENS integration via [ENS](https://ens.domains)
- Icons by [Lucide](https://lucide.dev)

## 📞 Support

- **Issues**: [GitHub Issues](https://github.com/bichain/bichain-farm/issues)
- **Discussions**: [GitHub Discussions](https://github.com/bichain/bichain-farm/discussions)

## 🔗 Links

- [Live Demo](https://bichain.github.io/bichain-farm/)
- [ApeChain Docs](https://docs.apechain.com)
- [MetaMask](https://metamask.io)
- [ENS Domains](https://ens.domains)

---

**Made with 🌱 by Bichain**

*Start farming on the blockchain today!* 🚜
