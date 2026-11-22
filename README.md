<div align="center">
  <a href="https://cdbc.io">
    <img src="https://raw.githubusercontent.com/Cloudbit-Global/core/main/assets/cdbc-logo-256.png" alt="Cloudbit Classic ($CDBC) Logo" width="135" height="135" />
  </a>
  <h1>Cloudbit Classic (<code>$CDBC</code>) – Core Registry &amp; Architecture</h1>
  <p><strong>Single Source of Truth for Verified Multichain Smart Contracts, Standard ABIs, Tokenomics &amp; Brand Assets</strong></p>
  <p>
    <a href="https://cdbc.io">cdbc.io</a> &bull;
    <a href="https://cloudbitex.com">cloudbitex.com (CloudbitDEX)</a> &bull;
    <a href="https://cdbc-api.vercel.app/api/cdbc/supply">Public API</a> &bull;
    <a href="https://cloudbit.to">cloudbit.to</a> &bull;
    <a href="https://t.me/cloudbit_ai_bot">@cloudbit_ai_bot</a> &bull;
    <a href="https://x.com/cloudbit_">X (@cloudbit_)</a>
  </p>
</div>

---

## Core Tokenomics

| Parameter | Specification |
| :--- | :--- |
| **Project Name** | Cloudbit Classic |
| **Ticker / Symbol** | CDBC (`$CDBC`) |
| **Total Supply** | `200,000,000 CDBC` (Fixed Maximum Supply) |
| **Buy / Sell Tax** | `0% Buy Tax / 0% Sell Tax` |
| **Primary Network** | BNB Smart Chain (BSC / BEP-20) |
| **Decimals** | `18` (EVM Standard) |

---

## Verified Smart Contract Registry

### Primary Main Contract
* **BNB Smart Chain (BEP-20):** `0xaf8b1b1bb4a47f537932968C7DE6E251dd50C6a9` ([BscScan](https://bscscan.com/token/0xaf8b1b1bb4a47f537932968C7DE6E251dd50C6a9))

### Verified Multichain Bridge Contracts
| Network | Standard | Verified Contract Address | Block Explorer |
| :--- | :--- | :--- | :--- |
| **Ethereum** | ERC-20 | `0xf2fef8fa2c52b927c0a589a1a645c77189f24541` | [Etherscan](https://etherscan.io/token/0xf2fef8fa2c52b927c0a589a1a645c77189f24541) |
| **Arbitrum One** | ERC-20 | `0xdc95becd16081bf00c3cabac5820a3e18b495cad` | [Arbiscan](https://arbiscan.io/token/0xdc95becd16081bf00c3cabac5820a3e18b495cad) |
| **Polygon (PoS)** | ERC-20 | `0x026a2ede22cc9525793120a3763d3a1c2c6840a8` | [Polygonscan](https://polygonscan.com/token/0x026a2ede22cc9525793120a3763d3a1c2c6840a8) |
| **Optimism** | ERC-20 | `0x92f1950d8c80a2d844b321e65e226a694801cc13` | [Optimistic Etherscan](https://optimistic.etherscan.io/token/0x92f1950d8c80a2d844b321e65e226a694801cc13) |
| **Avalanche C-Chain** | ARC-20 | `0x7462617313b26d7b72daed71a852e51588f7f1a7` | [Snowtrace](https://snowtrace.io/token/0x7462617313b26d7b72daed71a852e51588f7f1a7) |
| **Base** | ERC-20 | `0x35d545a52a8dd6abb588292ea6b7b9cb3898b53b` | [Basescan](https://basescan.org/token/0x35d545a52a8dd6abb588292ea6b7b9cb3898b53b) |
| **Solana** | SPL | `J74E2uSud3EH2aAUNLaxMRDyHde7oHDYopGLaim4DZta` | [Solscan](https://solscan.io/token/J74E2uSud3EH2aAUNLaxMRDyHde7oHDYopGLaim4DZta) |
| **Aptos** | Aptos Coin | `0x6917bec3bdfe7423619c1e128f8bebdc62405377aaf32365283e2ec5353fe1f7::coin::T` | [Aptos Explorer](https://explorer.aptoslabs.com/coin/0x6917bec3bdfe7423619c1e128f8bebdc62405377aaf32365283e2ec5353fe1f7::coin::T) |
| **Terra Classic** | CW-20 | `terra1q20zrqn278jm6e4a2z5ygky00h22l4js7wsge74xf4wwyald4r8qsyvyuj` | [Terra Finder](https://finder.terra.money/classic/address/terra1q20zrqn278jm6e4a2z5ygky00h22l4js7wsge74xf4wwyald4r8qsyvyuj) |

### 15-Chain Roadmap Expansion
* **Upcoming Bridge Integrations:** Sonic, NEAR, Sui, World, Terra, Cronos, Fantom, Gnosis, Kava, Moonbeam, Celo *(Upcoming Bridge Integration)*

---

## Machine-Readable Artifacts
* **[`registry/contracts.json`](https://raw.githubusercontent.com/Cloudbit-Global/core/main/registry/contracts.json)** – Full JSON registry (`v2.0.0`) with Chain IDs, explorers, and asset URLs.
* **[`abi/CDBC_BEP20.abi.json`](https://raw.githubusercontent.com/Cloudbit-Global/core/main/abi/CDBC_BEP20.abi.json)** – Verified BEP-20 contract ABI for BNB Smart Chain.
* **[`abi/CDBC_ERC20.abi.json`](https://raw.githubusercontent.com/Cloudbit-Global/core/main/abi/CDBC_ERC20.abi.json)** – Verified ERC-20 contract ABI for EVM bridge networks.
* **[`assets/cdbc-logo-256.png`](https://raw.githubusercontent.com/Cloudbit-Global/core/main/assets/cdbc-logo-256.png)** – Transparent `256x256 px` wallet-ready token icon.

---

## Official Cloudbit-Global Ecosystem Repositories
* **[`Cloudbit-Global/core`](https://github.com/Cloudbit-Global/core)** – Core architecture, multichain contract registry, verified ABIs, and brand assets.
* **[`Cloudbit-Global/cdbc-dex`](https://github.com/Cloudbit-Global/cdbc-dex)** – Official CloudbitDEX multichain decentralized exchange and listing portal (`cloudbitex.com`).
* **[`Cloudbit-Global/cdbc-app`](https://github.com/Cloudbit-Global/cdbc-app)** – Official main project portal and Android APK (`cdbc.io`).
* **[`Cloudbit-Global/cdbc-api`](https://github.com/Cloudbit-Global/cdbc-api)** – Public supply endpoints and OpenAPI 3.1 specifications (`cdbc-api.vercel.app`).
* **[`Cloudbit-Global/cdbc-bot`](https://github.com/Cloudbit-Global/cdbc-bot)** – Official Telegram GameFi & Tap2Earn Bot (`@cloudbit_ai_bot` / `cloudbit.to`).