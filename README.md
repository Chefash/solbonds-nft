# ☀️ SOLBonds - Sustainable NFT Matchmaking Protocol

> **NFT dating game meets DeFi yield - where compatibility earns real rewards**

![SOLBonds Banner](favicon-logo.png)

---

## 🎯 The Problem

Traditional NFT projects promise unsustainable APRs that inevitably drain reward pools and collapse, leaving users with worthless tokens and broken promises.

---

## 💡 Our Solution

**SOLBonds** is a matchmaking protocol where NFT pairs earn sustainable rewards based on:

- **Compatibility Score (0-100%):** Better matches = higher multipliers
- **Bond Duration:** Longer commitment = exponential rewards
- **Real DeFi Yield:** Backed by Solana's best protocols, not printed tokens

---

## 🔥 Key Features

### Compatibility Algorithm

Multi-factor matching system:

| Factor | Weight | Description |
|--------|--------|-------------|
| **Gender Alignment** | 20% | Masculine/Feminine preference matching |
| **Zodiac Compatibility** | 30% | Astrological harmony (Fire, Earth, Air, Water) |
| **Pet Preferences** | 25% | Dog person + Cat person = conflict! |
| **Risk Tolerance** | 25% | Trading behavior compatibility |

**Result:** 0-100% compatibility score that determines reward multipliers.

---

### ⏰ Time-Based Reward Tiers

| Duration | Multiplier | Tier |
|----------|------------|------|
| Days 1-7 | 1.0x | 🥉 Bronze |
| Days 8-30 | 1.5x | 🥈 Silver |
| Days 31-90 | 2.5x | 🥇 Gold |
| Days 91-180 | 4.0x | 💎 Diamond |
| Days 181+ | 6.0x | 👑 Legendary |

---

### 💕 Compatibility Multipliers

| Score | Multiplier | Status |
|-------|------------|--------|
| 90-100% | 2.0x | 🔥 Soulmates |
| 80-89% | 1.5x | 💕 Great match |
| 70-79% | 1.2x | 💛 Good match |
| 60-69% | 1.0x | ⚡ Base rate |
| Below 60% | 0.8x | 😅 Penalty |

---

## 💰 Sustainable Economics

### Revenue Sources (Daily)

```
Total Daily Inflow: $55.96

├─ DeFi Vault Yield: $10.96/day (8% APY on $50K)
│  ├─ 40% Kamino Finance ($20K @ 24% APY)
│  ├─ 25% MarginFi ($12.5K @ 12% APY)
│  ├─ 15% Sanctum ($7.5K @ 6% APY)
│  ├─ 10% Orca Treasury ($5K @ 5% APY)
│  └─ 10% SolBlaze LST ($5K @ 7% APY)
│
├─ User Activity Fees: $45/day
│  ├─ Mint Fees ($5 × 5 users/day)
│  ├─ Breakup Penalties ($5 × 2 breakups/day)
│  ├─ Discovery Bets ($1-10, avg $5 × 2/day)
│  └─ Boost Stakes ($3 × 3 users/day)
```

### The Formula

```
Daily Earnings = (Real Yield + User Fees) ÷ Active Pairs × Time Tier × Compatibility
```

**Example:**
```
($55.96 ÷ 50 pairs) × 2.5 (Gold Tier) × 1.5 (85% compat) = $4.20/day per pair
```

### Why It's Sustainable

- ✅ **No Printed Tokens:** Only distribute real revenue
- ✅ **Growing Vault:** Principal compounds via DeFi yield
- ✅ **Multiple Revenue Streams:** Not reliant on new users
- ✅ **Deflationary Pressure:** Breakup fees replenish pool
- ✅ **Transparency:** All numbers visible on dashboard

---

## 🎮 User Experience Flow

### 1. Profile Creation (0.01 SOL mint fee)
- Choose gender preference
- Select zodiac sign
- Pick pet preference
- Set risk tolerance

### 2. Discovery Phase (Optional boosts)
- 👀 Quick Peek: 2 USDC
- 🔮 Deep Reveal: 5 USDC
- 💎 Full Unlock: 10 USDC

### 3. Matching
- Algorithm calculates compatibility
- View match details
- Accept or pass

### 4. Bonding
- NFTs visually "merge"
- Earnings start immediately
- Dashboard shows real-time rewards

### 5. Relationship Management
- **Stay bonded:** Earnings compound
- **Break up:** Pay 0.005 SOL penalty

---

## 🛠️ Technical Implementation

### Tech Stack

| Layer | Technology |
|-------|------------|
| **Frontend** | HTML5, Tailwind CSS, Vanilla JavaScript |
| **Blockchain** | Solana (Web3.js) |
| **Wallet** | Phantom Integration |
| **Network** | Devnet (Mainnet ready) |

### Solana Integration

```javascript
// Real wallet connection
const { solana } = window;
const response = await solana.connect();

// Real transactions
const transaction = new solanaWeb3.Transaction();
transaction.add(solanaWeb3.SystemProgram.transfer({
    fromPubkey: userWallet,
    toPubkey: treasuryWallet,
    lamports: amount * LAMPORTS_PER_SOL
}));
```

### Key Data Structures

```rust
pub struct UserProfile {
    pub owner: Pubkey,
    pub username: String,
    pub gender: u8,
    pub zodiac: u8,
    pub pet: u8,
    pub risk: u8,
    pub is_bonded: bool,
    pub created_at: i64,
}

pub struct Bond {
    pub profile_a: Pubkey,
    pub profile_b: Pubkey,
    pub compatibility: u8,
    pub start_time: i64,
    pub total_claimed: u64,
    pub is_active: bool,
}
```

---

## 📊 Example Economics (90-Day Projection)

### Launch Conditions
- 100 NFTs minted: $500 → Vault
- Initial vault: $50,000 USDC
- 50 pairs formed

### Day 90 Results
- Vault: $50,985 (grown from yield)
- 50 pairs bonded
- **Top earners** (Legendary, 95% compat): $8.40/day
- **Average earners** (Gold, 85% compat): $4.20/day

### ROI Example
- User paid 0.01 SOL mint fee
- Found 92% compatibility match
- Stayed bonded 90 days
- **Total earnings: $168**
- **ROI: 3,260%** 🚀

---

## 🏆 Why SOLBonds Wins

### Innovation
- ✅ First protocol combining NFT matchmaking + sustainable DeFi yield
- ✅ Compatibility-weighted rewards (unique mechanism)
- ✅ Real Solana transactions

### Product Quality
- ✅ Beautiful, intuitive UI with smooth animations
- ✅ Complete user flow (onboarding → earning → claiming)
- ✅ Real-time reward calculations
- ✅ Transparent economics dashboard

### Technical Execution
- ✅ Real Phantom wallet integration
- ✅ Live transactions on Solana Devnet
- ✅ Sustainable tokenomics (no infinite minting)
- ✅ Privacy-preserving compatibility algorithm

### Market Fit
- ✅ Solves NFT utility problem
- ✅ Gamifies DeFi yield in accessible way
- ✅ Viral potential ("My NFT is in a relationship")
- ✅ Real financial incentives for engagement

---

## 🚀 Roadmap

### Phase 1: MVP (Hackathon) ✅
- ✅ Compatibility algorithm
- ✅ Time-based reward tiers
- ✅ Sustainable tokenomics model
- ✅ Frontend with Solana integration
- ✅ Real wallet transactions

### Phase 2: Launch
- Deploy to Solana mainnet
- Integrate Kamino Finance vault
- Real USDC rewards
- NFT art generation
- Mobile app

### Phase 3: Scale
- AI-powered compatibility
- "Double Date" mode (4-way bonds)
- NFT trait evolution
- Cross-chain expansion
- Dating app partnerships

### Phase 4: Ecosystem
- $BOND governance token
- Community treasury
- Partner integrations
- IRL meetup events

---

## 📹 Demo & Links

| Resource | Link |
|----------|------|
| 🌐 **Live Demo** | [chefash.github.io/solbonds-hackathon](https://chefash.github.io/solbonds-hackathon/) |
| 💻 **GitHub** | [github.com/Chefash/solbonds-hackathon](https://github.com/Chefash/solbonds-hackathon) |
| 🐦 **Twitter** | [@solbondsNFT](https://twitter.com/solbondsNFT) |
| 💬 **Discord** | [discord.gg/zF2edcJNCJ](https://discord.gg/zF2edcJNCJ) |
| 📧 **Email** | SolBonds.NFT@yahoo.com |

---

## 👥 Team

Built by a passionate vibes coder for the **Indie.fun Hackathon 2025**.

---

## 📄 License

MIT License - Build on it, fork it, make it yours!

---

<div align="center">

**Built for Indie.fun Hackathon 2025** | Solana DeFi × Social Gaming

### ☀️ Find Your SOLmate 💕

</div>
