# Portfolio
The repository serves as a comprehensive showcase of my experience in blockchain security, with a primary focus on conducting thorough smart contract security audits, participating in challenging bug bounty contests, and Capture The Flag (CTF) events. These experiences have honed my skills in identifying vulnerabilities, assessing potential risks, and proposing effective solutions within the blockchain ecosystem. 

Additionally, the repository includes a collection of in-depth summary articles I've authored, which delve into various aspects of smart contract security, providing valuable insights and best practices for developers and auditors alike.

## Profile
* [LinkedIn](https://www.linkedin.com/in/kritsada-dechawattana-426b58151/)
* [CodeHawks (JokerStudio)](https://profiles.cyfrin.io/u/jokerstudio)
* [Sherlock (JokerStudio)](https://audits.sherlock.xyz/watson/JokerStudio)


## Highlights
💡 **Deposits on long one leverage vault don't actually finalize the flow, leading to a Denial of Service (DoS)**
> This causes a Denial of Service (DoS) for the long one leverage vault, rendering the vault useless since it cannot proceed with another flow.
>
> 🔗 [2025-02-gamma-issues-#568](https://codehawks.cyfrin.io/c/2025-02-gamma/s/568)

💡 **Loss of fee refund due to premature state deletion in `PerpetualVault::_handleReturn` function**
> The user will lose all fee without getting any refund and the execution fee becomes stuck in the `GmxProxy` contract.
>
> 🔗 [2025-02-gamma-issues-#569](https://codehawks.cyfrin.io/c/2025-02-gamma/s/569)
---

## Team Audits

| Report                              | Date | Team   |
| ----------------------------------- | --   | ----   |
| [(Private) FWX - Future Trading](https://fwx.finance/)| October 2024 | [Valix](https://github.com/valixconsulting) |
| [(Private) FWX - Permissionless Future Trading](https://fwx.finance/)| October 2024 | [Valix](https://github.com/valixconsulting) |
| [(Private) FWX - DeFi Perpeptual Futures](https://fwx.finance/)| September 2024 | [Valix](https://github.com/valixconsulting) |
| [(Private) REAME - Token & NFT Smart Contract](https://reame.io/)| April 2024 | [Valix](https://github.com/valixconsulting) |
| [(Private) Starlet - Music NFT Smart Contract](https://www.starlet.world/)| April 2024 | [Valix](https://github.com/valixconsulting) |
| [(Private) FWX - Permissionless Future Trading](https://fwx.finance/)| March 2024 | [Valix](https://github.com/valixconsulting) |
| [BIG BANG THEORY - Smart Contract (Token & NFT)](https://github.com/valixconsulting/audit-reports/blob/main/ValixConsulting-Audit-Report-TheBigbangTheory-Final-v1.0.pdf)| September 2023 | [Valix](https://github.com/valixconsulting) |
| [NFTGT Co., Ltd. - NFTGT Factory and Contract](https://github.com/valixconsulting/audit-reports/blob/main/ValixConsulting-Audit-Report-CodeSekai-NFT-Minting-and-Transferring-In-game-Out-game-v1.1.pdf)| April 2023 | [Valix](https://github.com/valixconsulting) |
| [Code Sekai - NFT Minting & Transferring In-game/Out-game](https://github.com/valixconsulting/audit-reports/blob/main/ValixConsulting-Audit-Report-CodeSekai-NFT-Minting-and-Transferring-In-game-Out-game-v1.1.pdf)| April 2023 | [Valix](https://github.com/valixconsulting) |
| [Xtatuz DMCC - XTATUZ asset tokenization](https://github.com/valixconsulting/audit-reports/blob/main/ValixConsulting-Audit-Report-XtatuzDMCC-XTATUZ-Asset-Tokenization-v1.0.pdf)| March 2023 | [Valix](https://github.com/valixconsulting) |
| [Vega Investment Group Limited - CrownToken and VucaStaking](https://github.com/valixconsulting/audit-reports/blob/main/ValixConsulting-Audit-Report-VegaInvestmentGroupLimited-CrownToken-and-VucaStaking-v1.0.pdf)| December 2022 | [Valix](https://github.com/valixconsulting) |
| [Vega Investment Group Limited - CrownToken](https://github.com/valixconsulting/audit-reports/blob/main/ValixConsulting-Audit-Report-VegaInvestmentGroupLimited-CrownToken-v1.0.pdf)| November 2022 | [Valix](https://github.com/valixconsulting) |
| [Aniverse - ANIV721Land](https://github.com/valixconsulting/audit-reports/blob/main/ValixConsulting-Audit-Report-Aniverse-ANIV721Land-v1.0.pdf)| September 2022 | [Valix](https://github.com/valixconsulting) |
| [Warden Finance - Wondrous-X](https://github.com/valixconsulting/audit-reports/blob/main/ValixConsulting-Audit-Report-WardenFinance-Wondrous-X-v1.0.pdf)| September 2022 | [Valix](https://github.com/valixconsulting) |

---

## Bug Bounty Contests

| Contest | Type | Awards | Findings | Language | Date | @ |Platform | Contest Report | My Report |
|:--:|:--:|:--:|:--:| ---- | -------- |:--:|:--:|:--:|:--:|
| [Gamma - Liquidity Management](https://codehawks.cyfrin.io/c/2025-02-gamma) | The Perpetual Vault Protocol | 36th | 2H | Solidity | Feb 2025 | Individual | CodeHawks | [📑](https://codehawks.cyfrin.io/c/2025-02-gamma/results?lt=contest&page=1&sc=reward&sj=reward&t=report) | [💾](./sherlock/2024-08-flayer.md) |
| [Flayer - NFT Liquidity Protocol](https://audits.sherlock.xyz/contests/468) | NFT Liquidity Protocol, Uniswap v4 Hooks | 65th | 1M | Solidity | Sep 2024 | Individual | Sherlock | [📑](https://audits.sherlock.xyz/contests/468/report) | [💾](./codehawks/2025-02-gamma.md) |


---

## CTF rankings

| CTF  | Year   | Ranking | Reference |
|------|--------| --------| ------- |
| ONLYPWNER | 2024 | 15 challs solved | [https://onlypwner.xyz/leaderboard](https://onlypwner.xyz/leaderboard) |
| Damn Vulnerable DeFi V3 | 2023 | All challs solved | [https://github.com/jokerstudio/damn-vulnerable-defi-solution](https://github.com/jokerstudio/damn-vulnerable-defi-solution) |

___

## Blogs
| Title | Date |
|-------|------|
| [Cairo for Solidity Developer and Smart Contract Auditor](https://medium.com/@kritsada-d/cairo-for-solidity-developer-and-smart-contract-auditor-ed9b81a4cb30) | October 2024 |
| [EIP7702: Closing the Gap Between EOAs and Smart Contracts](https://medium.com/valixconsulting/eip7702-closing-the-gap-between-eoas-and-smart-contracts-16b6f05584a9) | September 2024 |
| [Upgradeable Smart Contract](https://medium.com/valixconsulting/upgradeable-smart-contract-db415a1ea17) | October 2023 |
