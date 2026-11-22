# Security Policy

## Scope

This policy covers all repositories and production services under `Cloudbit-Global`:

| Repository | Scope | Status |
| :--- | :--- | :--- |
| `Cloudbit-Global/core` | Multichain contract registry & verified ABIs | Active |
| `Cloudbit-Global/cdbc-dex` | CloudbitDEX (`cloudbitex.com`), TokenList & APK | Active |
| `Cloudbit-Global/cdbc-app` | Main ecosystem portal (`cdbc.io`) & APK | Active |
| `Cloudbit-Global/cdbc-api` | Public Vercel Supply API (`cdbc-api.vercel.app`) | Active |
| `Cloudbit-Global/cdbc-bot` | Telegram Mini App (`@cloudbit_ai_bot` / `cloudbit.to`) & APK | Active |

## Canonical On-Chain Invariants

* **Primary Main Contract (BNB Smart Chain / BEP-20):** `0xaf8b1b1bb4a47f537932968C7DE6E251dd50C6a9`
* **Fixed Maximum Supply:** `200,000,000 CDBC`
* **Token Tax:** `0% Buy Tax / 0% Sell Tax`
* **CloudbitDEX Swap Fee:** `0.25%` Protocol Router Fee + `0.25%` Liquidity Provider Fee

Always cross-verify contract addresses against `Cloudbit-Global/core/registry/contracts.json` and verify Android APK installers against their `.sha256` release checksums.

## Reporting a Vulnerability

**Do not open public GitHub issues for security vulnerabilities.**

Report suspected vulnerabilities privately via GitHub Private Vulnerability Reporting (Security tab on the affected repository) or through official project channels listed on `https://cdbc.io` and `https://x.com/cloudbit_`. Include reproduction steps, affected component/version, and potential impact. Maintainers aim to acknowledge reports within 48 hours.
