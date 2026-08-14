import os
from weasyprint import HTML

md_content = """<div align="center">
  <!-- Replace with actual raw image URL if desired, currently using a placeholder block to represent the header -->
  <h1>🌐 Cloudbit Classic ($CDBC)</h1>
  <p><b>Innovative P2P Cryptocurrency & Multichain Platform</b></p>

  [![Network](https://img.shields.io/badge/Network-BSC-F3BA2F?style=for-the-badge&logo=binance)](https://bscscan.com/token/0xaf8b1b1bb4a47f537932968C7DE6E251dd50C6a9)
  [![Type](https://img.shields.io/badge/Type-BEP--20-blue?style=for-the-badge)](https://cloudbitex.com)
  [![Tax](https://img.shields.io/badge/Tax-0%25-success?style=for-the-badge)]()
  [![Community](https://img.shields.io/badge/Community-Join_Us-0088cc?style=for-the-badge&logo=telegram)](https://linktr.ee/cloudbit)
</div>

<br>

## 📖 About Cloudbit Classic (CDBC)
Founded in 2019, **Cloudbit** represents a decentralized ecosystem engineered to enable seamless communication between diverse blockchains and their smart contracts.

CDBC powers a network driven by a massive community of data processing providers, node operators, smart contract developers, and security auditors. We bridge the gap by providing external data, events, payment methods, and off-chain information processing—all while ensuring decentralized participation remains globally accessible.

---

## 💎 Tokenomics

| Feature | Details |
| :--- | :--- |
| **Name** | Cloudbit Classic |
| **Symbol** | `$CDBC` |
| **Network** | Binance Smart Chain (BSC) |
| **Type** | BEP-20 |
| **Decimals** | 18 |
| **Total Supply** | 200,000,000 CDBC (100%) |
| **Burned** | 2,000,000 CDBC (1%) 🔥 |
| **Buy/Sell Tax** | 0% 💸 |

> **Official Main Contract Address (BSC):**
> `0xaf8b1b1bb4a47f537932968C7DE6E251dd50C6a9`

---

## 🌍 Multichain Architecture & Smart Contracts
Cloudbit Classic isn't limited to a single chain. Our robust cross-chain bridge architecture extends $CDBC across the following networks:

*   🟡 **Main-CA:** Smart Chain Network (BSC)
*   🔵 **Bridge-CAs:**
    *   Ethereum Network (ETH)
    *   Arbitrum Network (ARB)
    *   Polygon Network (MATIC)
    *   Optimism Network (OP)
    *   Avalanche C-Network (AVAX)
    *   Sonic Mainnet Network (S)
    *   Aptos Chain Network (APT)
    *   Base Mainnet Network (BASE)
    *   Solana Network (SOL)
    *   Terra Classic Network (LUNC)
    *   Terra Mainnet Network (LUNA)

---

## 🚀 Roadmap

### 🟢 Phase 1: Preparations
- [x] New Whitepaper, One-Pager, and Pitch-Deck documents
- [x] New Website Design
- [x] Upgraded Infrastructure within the Cloudbit Ecosystem
- [x] Creation of Cloudbit Classic (CDBC)
- [x] $CDBC Audited by AnalytixAudit
- [x] Press Release Distribution by King NewsWire

### 🟡 Phase 2: $CDBC Coin Launch
- [ ] Crosschain/Multichain Bridge Implementation
- [ ] Obtain SAFU & KYC Badge
- [ ] Fair Launch on Pinksale
- [ ] Staking Pool on GemPad (Stake CDBC / Earn CDBC)
- [ ] CG (CoinGecko) and CMC (CoinMarketCap) Listings
- [ ] Reach 1,000+ Holders

### 🟠 Phase 3: Vibe and HODL
- [ ] Community Partnerships & *CDBC Times* Digital Newsletter
- [ ] Token-Gated Telegram Group for Holders
- [ ] Get $CDBC Trending on Twitter
- [ ] Initial CEX Listings
- [ ] Reach 10,000+ Holders

### 🔴 Phase 4: Coin Takeover
- [ ] CDBC Academy, Merch, and Tools rollout
- [ ] Tier 1 (T1) Exchange Listings
- [ ] Coin Takeover initiatives
- [ ] Reach 100,000+ Holders

---

## 📚 Documentation & Resources
Access all our technical and promotional materials below:

- 📄 [Whitepaper](#) | 📄 [One-Pager](#) | 📄 [Pitch-Deck](#)
- 🛡️ [Audit-Report](#)
- 🗳️ [Voting-Provider](#)
- 📜 [Terms of Coin Sale](#)

---

## 🌐 Official Links & Contact
Stay updated and join the Cloudbit community!

- 🌐 **Web:** [cloudbitex.com](https://cloudbitex.com)
- 🔌 **API:** [CDBC-API](https://cdbc.io)
- 🌳 **All Links:** [Linktree](#)
- ✉️ **Contact Us:** [Get in touch](#)

<br>
<div align="center">
  <i>Built with ❤️ by the Cloudbit Global Team</i>
</div>
"""

with open('Cloudbit_Classic_README.md', 'w', encoding='utf-8') as f:
    f.write(md_content)

html_content = """
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<style>
@page {
    size: A4;
    margin: 15mm 15mm;
    background-color: #0d1117;
}
body {
    margin: 0;
    padding: 0;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
    color: #c9d1d9;
    background-color: #0d1117;
    font-size: 11pt;
    line-height: 1.6;
    box-sizing: border-box;
}
*, *::before, *::after {
    box-sizing: border-box;
}
h1, h2, h3 {
    color: #58a6ff;
    border-bottom: 1px solid #30363d;
    padding-bottom: 5px;
}
h1 { font-size: 20pt; text-align: center; border: none; margin-bottom: 0; color: #ffffff; }
h2 { font-size: 15pt; margin-top: 20px; page-break-after: avoid; }
h3 { font-size: 12pt; color: #8b949e; border: none; margin-top: 15px; page-break-after: avoid; }
p, li { margin-bottom: 10px; }
table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 10px;
    margin-bottom: 10px;
}
th, td {
    border: 1px solid #30363d;
    padding: 8px 12px;
    text-align: left;
}
th { background-color: #161b22; color: #c9d1d9; font-weight: bold; }
a { color: #58a6ff; text-decoration: none; }
.badge {
    display: inline-block;
    padding: 4px 8px;
    border-radius: 4px;
    font-size: 9pt;
    font-weight: bold;
    margin: 2px;
}
.badge-bsc { background-color: #F3BA2F; color: #000; }
.badge-blue { background-color: #1f6feb; color: #fff; }
.badge-green { background-color: #238636; color: #fff; }
.center { text-align: center; }
ul { padding-left: 20px; }
.checkbox { font-family: monospace; }
.header-subtitle { text-align: center; font-weight: bold; color: #8b949e; margin-top: 5px; }
.callout {
    background-color: #161b22;
    border-left: 4px solid #58a6ff;
    padding: 10px;
    margin: 10px 0;
    page-break-inside: avoid;
}
</style>
</head>
<body>
    <h1>🌐 Cloudbit Classic ($CDBC)</h1>
    <div class="header-subtitle">Innovative P2P Cryptocurrency & Multichain Platform</div>
    <div class="center" style="margin-top: 10px;">
        <span class="badge badge-bsc">Network: BSC</span>
        <span class="badge badge-blue">Type: BEP-20</span>
        <span class="badge badge-green">Tax: 0%</span>
    </div>

    <h2>📖 About Cloudbit Classic (CDBC)</h2>
    <p>Founded in 2019, <strong>Cloudbit</strong> represents a decentralized ecosystem engineered to enable seamless communication between diverse blockchains and their smart contracts.</p>
    <p>CDBC powers a network driven by a massive community of data processing providers, node operators, smart contract developers, and security auditors. We bridge the gap by providing external data, events, payment methods, and off-chain information processing—all while ensuring decentralized participation remains globally accessible.</p>

    <h2>💎 Tokenomics</h2>
    <table>
        <tr><th>Feature</th><th>Details</th></tr>
        <tr><td><strong>Name</strong></td><td>Cloudbit Classic</td></tr>
        <tr><td><strong>Symbol</strong></td><td>$CDBC</td></tr>
        <tr><td><strong>Network</strong></td><td>Binance Smart Chain (BSC)</td></tr>
        <tr><td><strong>Type</strong></td><td>BEP-20</td></tr>
        <tr><td><strong>Decimals</strong></td><td>18</td></tr>
        <tr><td><strong>Total Supply</strong></td><td>200,000,000 CDBC (100%)</td></tr>
        <tr><td><strong>Burned</strong></td><td>2,000,000 CDBC (1%)</td></tr>
        <tr><td><strong>Buy/Sell Tax</strong></td><td>0%</td></tr>
    </table>
    <div class="callout">
        <strong>Official Main Contract Address (BSC):</strong><br>
        <code>0xaf8b1b1bb4a47f537932968C7DE6E251dd50C6a9</code>
    </div>

    <h2>🌍 Multichain Architecture & Smart Contracts</h2>
    <p>Cloudbit Classic isn't limited to a single chain. Our robust cross-chain bridge architecture extends $CDBC across the following networks:</p>
    <ul>
        <li>🟡 <strong>Main-CA:</strong> Smart Chain Network (BSC)</li>
        <li>🔵 <strong>Bridge-CAs:</strong> Ethereum (ETH), Arbitrum (ARB), Polygon (MATIC), Optimism (OP), Avalanche C-Network (AVAX), Sonic Mainnet (S), Aptos Chain (APT), Base Mainnet (BASE), Solana (SOL), Terra Classic (LUNC), Terra Mainnet (LUNA)</li>
    </ul>

    <h2>🚀 Roadmap</h2>
    <h3>🟢 Phase 1: Preparations</h3>
    <ul>
        <li><span class="checkbox">[x]</span> New Whitepaper, One-Pager, and Pitch-Deck documents</li>
        <li><span class="checkbox">[x]</span> New Website Design</li>
        <li><span class="checkbox">[x]</span> Upgraded Infrastructure within the Cloudbit Ecosystem</li>
        <li><span class="checkbox">[x]</span> Creation of Cloudbit Classic (CDBC)</li>
        <li><span class="checkbox">[x]</span> $CDBC Audited by AnalytixAudit</li>
        <li><span class="checkbox">[x]</span> Press Release Distribution by King NewsWire</li>
    </ul>
    <h3>🟡 Phase 2: $CDBC Coin Launch</h3>
    <ul>
        <li><span class="checkbox">[ ]</span> Crosschain/Multichain Bridge Implementation</li>
        <li><span class="checkbox">[ ]</span> Obtain SAFU & KYC Badge</li>
        <li><span class="checkbox">[ ]</span> Fair Launch on Pinksale & Staking Pool on GemPad</li>
        <li><span class="checkbox">[ ]</span> CG (CoinGecko) and CMC (CoinMarketCap) Listings</li>
        <li><span class="checkbox">[ ]</span> Reach 1,000+ Holders</li>
    </ul>
    <h3>🟠 Phase 3: Vibe and HODL</h3>
    <ul>
        <li><span class="checkbox">[ ]</span> Community Partnerships & CDBC Times digital newsletter</li>
        <li><span class="checkbox">[ ]</span> Token-Gated Telegram Group for Holders</li>
        <li><span class="checkbox">[ ]</span> Initial CEX Listings & Reach 10,000+ Holders</li>
    </ul>
    <h3>🔴 Phase 4: Coin Takeover</h3>
    <ul>
        <li><span class="checkbox">[ ]</span> CDBC Academy, Merch, and Tools rollout</li>
        <li><span class="checkbox">[ ]</span> Tier 1 (T1) Exchange Listings & Reach 100,000+ Holders</li>
    </ul>

    <h2>📚 Documentation & Resources</h2>
    <p>Access all our technical and promotional materials:</p>
    <ul>
        <li>📄 Whitepaper | One-Pager | Pitch-Deck</li>
        <li>🛡️ Audit-Report</li>
        <li>🗳️ Voting-Provider</li>
        <li>📜 Terms of Coin Sale</li>
    </ul>

    <h2>🌐 Official Links & Contact</h2>
    <ul>
        <li>🌐 <strong>Web:</strong> cloudbitex.com</li>
        <li>🔌 <strong>API:</strong> cdbc.io</li>
        <li>🌳 <strong>All Links:</strong> Linktree</li>
    </ul>
    <div class="center" style="margin-top:20px; font-style:italic; color:#8b949e;">
        Built with ❤️ by the Cloudbit Global Team
    </div>
</body>
</html>
"""
HTML(string=html_content).write_pdf('Cloudbit_Classic_README_Preview.pdf')

print("Files generated successfully.")

