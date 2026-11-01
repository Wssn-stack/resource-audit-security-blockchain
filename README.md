# Resource Audit / Security Blockchain

A curated repository of high-signal resources for blockchain security, smart contract auditing, and DeFi protocol research.

This repo is intentionally focused on the most useful and legitimate references for people who want to become:
- smart contract security engineer
- DeFi researcher / protocol specialist
- blockchain auditor
- protocol analyst

The structure is designed to reduce information overload and help you move from foundational knowledge to advanced protocol-level reasoning.

## Why this repo exists

Most blockchain learning resources are either:
- too shallow and beginner-oriented,
- too broad and chaotic,
- or too academic without a clear path to practical security understanding.

This repository focuses on the path that matters most:

1. Learn the Ethereum / EVM foundation
2. Learn Solidity and contract design patterns
3. Learn DeFi primitives and protocol economics
4. Learn common exploits and attack vectors
5. Learn how to reason about protocol risk as a system

---

## Track 1: Security Engineer

### 1. Core blockchain fundamentals
- Ethereum docs: https://ethereum.org/en/developers/docs/
- Mastering Ethereum: https://github.com/ethereumbook/ethereumbook
- Solidity docs: https://docs.soliditylang.org/
- EVM docs and opcode references: https://www.evm.codes/
- EVM deep dives and practical explanations:
  - https://noxx.substack.com/
  - https://github.com/mektigboy/evm-chad
  - https://mudit.blog/
  - https://www.zaryabs.com/ethereum-virtual-machine-article-series/
- Learn Git and terminal basics: https://git-scm.com/doc
- Linux / Docker basics: https://docs.docker.com/

### 2. Solidity and smart contract security
- Solidity by Example: https://solidity-by-example.org/
- OpenZeppelin docs: https://docs.openzeppelin.com/contracts/
- ConsenSys best practices: https://consensys.github.io/smart-contract-best-practices/
- Secure smart contract development materials:
  - https://secure-contracts.com/
  - https://github.com/jcr-security/solidity-security-teaching-resources
- Basic security checklist for contracts:
  - https://github.com/ComposableSecurity/SCSVS
  - https://github.com/ComposableSecurity/SCSVS

### 3. Attack patterns and vulnerability classes
- Reentrancy and common contract issues:
  - https://arxiv.org/pdf/2105.06974.pdf
  - https://github.com/uni-due-syssec/eth-reentrancy-attack-patterns
- Smart contract attack vectors and bug patterns:
  - https://github.com/KadenZipfel/smart-contract-attack-vectors
  - https://github.com/crytic/not-so-smart-contracts
  - https://github.com/freight-chain/defi-sec
  - https://github.com/freight-trust/defi-threat
- All known Web3 attack patterns:
  - https://graph.org/All-known-smart-contract-side-and-user-side-attacks-and-vulnerabilities-in-Web30--DeFi-03-31
- DeFi-specific vulnerabilities and postmortems:
  - https://rekt.eth.link/leaderboard
  - https://magoo.github.io/Blockchain-Graveyard/
  - https://blockthreat.substack.com/

### 4. Security tooling
- Slither: https://github.com/crytic/slither
- Mythril: https://github.com/ConsenSys/mythril
- Manticore: https://github.com/trailofbits/manticore
- Oyente: https://github.com/melonproject/oyente
- Securify: https://securify.chainsecurity.com/
- SmartCheck: https://tool.smartdec.net/
- Echidna / fuzzing and invariant testing: https://github.com/crytic/echidna
- Foundry: https://book.getfoundry.sh/
- Hardhat: https://hardhat.org/

### 5. Practice labs and CTFs
- Ethernaut: https://ethernaut.openzeppelin.com/
- Damn Vulnerable DeFi: https://www.damnvulnerabledefi.xyz/
- Damn Vulnerable DeFi (Foundry): https://github.com/nicolasgarcia214/damn-vulnerable-defi-foundry
- Capture the Ether: https://capturetheether.com/
- Paradigm CTF: https://ctf.paradigm.xyz/
- CTF and security lab collections:
  - https://tryhackme.com/
  - https://www.hackthebox.com/
  - https://overthewire.org/wargames/
  - https://portswigger.net/web-security/all-labs

---

## Track 2: DeFi Researcher / Protocol Specialist

### 1. DeFi foundations
- SoK: Decentralized Finance (DeFi): https://arxiv.org/pdf/2101.08778.pdf
- DeFi-ning DeFi: Challenges & Pathway: https://arxiv.org/pdf/2101.05589.pdf
- A theory of Automated Market Makers in DeFi: https://arxiv.org/pdf/2102.11350.pdf
- On the Just-In-Time Discovery of Profit-Generating Transactions in DeFi Protocols: https://arxiv.org/pdf/2103.02228.pdf
- Maximizing Extractable Value from Automated Market Makers: https://arxiv.org/pdf/2106.01870.pdf
- Flash Boys 2.0: Frontrunning, Transaction Reordering, and Consensus Instability in Decentralized Exchanges: https://arxiv.org/pdf/1904.05234.pdf
- Formal Analysis of Composable DeFi Protocols: https://arxiv.org/pdf/2103.00540.pdf

### 2. AMM and DEX mechanics
- An analysis of Uniswap markets: https://arxiv.org/pdf/1911.03380.pdf
- Behavior of Liquidity Providers in Decentralized Exchanges: https://arxiv.org/pdf/2105.13822.pdf
- Composing Networks of Automated Market Makers: https://arxiv.org/pdf/2106.00083.pdf
- Dynamic Curves for Decentralized Autonomous Cryptocurrency Exchanges: https://arxiv.org/pdf/2101.02778.pdf
- Cyclic Arbitrage in Decentralized Exchange Markets: https://arxiv.org/pdf/2105.02784.pdf
- High-Frequency Trading on Decentralized On-Chain Exchanges: https://arxiv.org/pdf/2009.14021.pdf
- Blockchain Oracle Design Patterns: https://arxiv.org/abs/2106.09349

### 3. Lending, liquidation, and credit markets
- From banks to DeFi: the evolution of the lending market: https://arxiv.org/pdf/2104.00970.pdf
- Liquidations: DeFi on a Knife-edge: https://arxiv.org/pdf/2009.13235v4.pdf
- The Decentralized Financial Crisis: https://arxiv.org/pdf/2002.08099.pdf
- Measuring Asset Composability as a Proxy for DeFi Integration: https://arxiv.org/pdf/2102.04227.pdf

### 4. Stablecoins and peg design
- Stablecoins 2.0: https://arxiv.org/pdf/2006.12388.pdf
- Reducing the Volatility of Cryptocurrencies — A Survey of Stablecoins: https://arxiv.org/pdf/2103.01340.pdf
- Understand Volatility of Algorithmic Stablecoin: Modeling, Verification and Empirical Analysis: https://arxiv.org/pdf/2101.08423.pdf
- Pharos: https://pharos.watch/

### 5. Oracle and price manipulation
- SoK: Oracles from the Ground Truth to Market Manipulation: https://arxiv.org/pdf/2106.00667.pdf
- Blockchain Oracle Design Patterns: https://arxiv.org/abs/2106.09349
- Chainlink docs: https://docs.chain.link/
- TWAP and oracle risk analysis: https://docs.uniswap.org/

### 6. MEV and transaction ordering
- Flash Boys 2.0: https://arxiv.org/pdf/1904.05234.pdf
- Quantifying Blockchain Extractable Value: https://arxiv.org/pdf/2101.05511v2.pdf
- Flashbots: https://docs.flashbots.net/
- MEV in Ethereum and transaction ordering analysis:
  - https://hackmd.io/@flashbots/mev-in-eth2
- Research community:
  - https://ethresear.ch/
  - https://www.smartcontractresearch.org/

### 7. Governance, token design, and system analysis
- Empirical Evidence from four Governance Token Distributions: https://arxiv.org/pdf/2102.10096.pdf
- A Systematic Literature Review on Blockchain Governance: https://arxiv.org/pdf/2105.05460.pdf
- Security and governance analysis of systems with timelocks and role-based access control.

---

## Shared knowledge area: security + system thinking

This is the overlap between smart contract engineering and protocol research.

### Core concepts to master
- access control and ownership
- proxy patterns and upgradeability
- reentrancy and state consistency
- oracle manipulation
- ERC20 quirks and token integration risk
- fee-on-transfer and token transfer pitfalls
- governance capture and timelock assumptions
- emergency pause and admin recovery design
- liquidation and solvency assumptions
- composability risk across protocols
- economic incentives and exploitability

### Important readings
- Smart Contract Security best practices: https://consensys.github.io/smart-contract-best-practices/
- All known smart contract side and user side attacks: https://graph.org/All-known-smart-contract-side-and-user-side-attacks-and-vulnerabilities-in-Web30--DeFi-03-31
- Solidity audits and secure development material: https://github.com/jcr-security/solidity-security-teaching-resources
- SCSVS and security taxonomy: https://github.com/ComposableSecurity/SCSVS
- Security framework for protocol design: https://www.beirao.xyz/blog/Security-framework

---

## Common practical projects to develop skill

### For security engineers
- Build a vulnerable contract and then patch it
- Reproduce classic attacks:
  - reentrancy
  - oracle manipulation
  - access control bug
  - infinite approval bug
  - flashloan exploit chain
- Write custom tests using Foundry or Hardhat
- Run static analysis and fix warnings
- Compare contract analysis outputs from multiple tools

### For DeFi researchers
- Rebuild a simple AMM in Solidity
- Build a lending vault prototype with liquidation logic
- Model an oracle attack and its economic effect
- Simulate liquidation cascade under volatility stress
- Compare governance design options and attack assumptions
- Write a risk memo of a live protocol architecture

---

## High-value learning path

### If your goal is Security Engineer
- Ethereum + EVM fundamentals
- Solidity + safe patterns
- Static analysis tools
- Classic vulnerability classes
- Reproduction of exploits in CTFs/labs
- Contract testing + fuzzing
- Protocol-specific risk thinking

### If your goal is DeFi Researcher / Protocol Specialist
- DeFi primitives and protocol mechanics
- AMM / DEX logic
- Lending and liquidation theory
- Stablecoin design and peg risk
- Oracle manipulation and MEV
- Governance and incentive design
- Systemic risk and composability analysis

### If your goal is both
- Learn all of the above with strong overlap in:
  - EVM internals
  - Solidity
  - DeFi system design
  - exploit analysis
  - economic reasoning

---

## Recommended “legit” references from this domain

These are the most important references to consistently return to:

- Ethereum docs: https://ethereum.org/en/developers/docs/
- Solidity docs: https://docs.soliditylang.org/
- Mastering Ethereum: https://github.com/ethereumbook/ethereumbook
- EVM docs: https://www.evm.codes/
- OpenZeppelin docs: https://docs.openzeppelin.com/contracts/
- SoK: Decentralized Finance (DeFi): https://arxiv.org/pdf/2101.08778.pdf
- A theory of Automated Market Makers in DeFi: https://arxiv.org/pdf/2102.11350.pdf
- Flash Boys 2.0: https://arxiv.org/pdf/1904.05234.pdf
- SoK: Oracles from the Ground Truth to Market Manipulation: https://arxiv.org/pdf/2106.00667.pdf
- Ethernaut: https://ethernaut.openzeppelin.com/
- Damn Vulnerable DeFi: https://www.damnvulnerabledefi.xyz/
- Slither: https://github.com/crytic/slither
- Foundry: https://book.getfoundry.sh/
- Security checklist: https://github.com/ComposableSecurity/SCSVS
- DeFi security: https://github.com/freight-chain/defi-sec

---

## Final guidance

The strongest path is not to read everything. It is to build a repeated workflow:

1. Learn the primitive
2. Understand the protocol mechanism
3. Identify the failure mode
4. Model the exploit or risk scenario
5. Test or simulate the scenario
6. Write the security or protocol reasoning clearly

This is the core of blockchain security and DeFi research.

The best people in this space are not merely “smart contract coders.”
They think in terms of:
- protocol invariants
- incentive design
- exploit paths
- risk boundaries
- system behavior under stress

That is the actual skill gap between basic smart contract development and advanced blockchain security / DeFi research.

---

## Contribution note

This repo is intended to evolve over time. If you are working in blockchain security, auditing, or DeFi protocol analysis, you can contribute:
- newly discovered research papers,
- security benchmarks,
- notable postmortems,
- protocol analysis notes,
- foundational tools or docs,
- well-curated learning material.

The goal is to keep this repository useful, rigorous, and practical.

---

## License

This repository is for educational and research purposes only.

It is meant to be a resource hub for learning, not financial advice or an operational recommendation for live production systems.

---

## End note

If your aim is to become a serious blockchain security engineer or DeFi protocol specialist, treat this area as a mix of:
- engineering discipline,
- security analysis,
- economic reasoning,
- and protocol-level systems thinking.

That is the real path.
