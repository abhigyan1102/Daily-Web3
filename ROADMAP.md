# 🗺️ 8-Month Web3 / Blockchain Mastery Roadmap

> **Start Date:** March 20, 2026  
> **End Date:** November 20, 2026  
> **Daily Commitment:** 3–4 hours minimum  
> **Weekly Structure:** 5 days learning + 1 day building + 1 day review/post

---

## 🟢 MONTH 1 — Blockchain Foundations & Solidity Basics  
*Mar 20 – Apr 19 · Days 1–30*

### Week 1 (Days 1–7): How Blockchain Works
- [ ] Day 1: What is blockchain? Distributed ledger, decentralization, immutability
- [ ] Day 2: Cryptographic hashing (SHA-256), Merkle trees
- [ ] Day 3: Consensus mechanisms — PoW vs PoS vs DPoS vs BFT
- [ ] Day 4: Bitcoin architecture — UTXOs, mining, halvings
- [ ] Day 5: Ethereum architecture — accounts, gas, EVM
- [ ] Day 6: Wallets, private/public keys, signing transactions
- [ ] Day 7: **Week 1 Review** — write a blog post / X thread summarizing learnings

**Resources:**
- 📖 [Mastering Bitcoin (Ch 1-4)](https://github.com/bitcoinbook/bitcoinbook) — Andreas Antonopoulos
- 📖 [Mastering Ethereum (Ch 1-4)](https://github.com/ethereumbook/ethereumbook) — Andreas Antonopoulos
- 🎥 [Blockchain 101 — Anders Brownworth](https://andersbrownworth.com/blockchain/)
- 🎥 [MIT 15.S12 Blockchain and Money](https://www.youtube.com/playlist?list=PLUl4u3cNGP63UUkfL0onkxF6MYgVa04Fn)
- 📝 [Ethereum Whitepaper](https://ethereum.org/en/whitepaper/)

### Week 2 (Days 8–14): Solidity Fundamentals — Part 1
- [ ] Day 8: Set up dev environment — VS Code, Solidity extension, Remix IDE
- [ ] Day 9: Solidity data types — uint, int, bool, address, bytes, string
- [ ] Day 10: Variables — state vs local vs global, visibility modifiers
- [ ] Day 11: Functions — view, pure, payable, fallback, receive
- [ ] Day 12: Control flow — if/else, for/while loops, require/assert/revert
- [ ] Day 13: Arrays, mappings, structs, enums
- [ ] Day 14: **Mini Project** — Build a Simple Storage contract in Remix

**Resources:**
- 🎥 [Cyfrin Updraft — Solidity 101](https://updraft.cyfrin.io/courses/solidity) — Patrick Collins (FREE)
- 📖 [Solidity by Example](https://solidity-by-example.org/)
- 📖 [Solidity Docs](https://docs.soliditylang.org/)
- 🛠️ [Remix IDE](https://remix.ethereum.org/)

### Week 3 (Days 15–21): Solidity Fundamentals — Part 2
- [ ] Day 15: Inheritance, interfaces, abstract contracts
- [ ] Day 16: Events and logging
- [ ] Day 17: Error handling patterns — custom errors, try/catch
- [ ] Day 18: Modifiers, constructor, selfdestruct
- [ ] Day 19: Ether transfers — transfer(), send(), call()
- [ ] Day 20: Storage, memory, calldata — understanding the EVM memory model
- [ ] Day 21: **Mini Project** — Build a Crowdfunding contract

**Resources:**
- 🎥 [Cyfrin Updraft — Solidity 101](https://updraft.cyfrin.io/courses/solidity) (continue)
- 📖 [Solidity Patterns](https://fravoll.github.io/solidity-patterns/)
- 📖 [OpenZeppelin Contracts](https://docs.openzeppelin.com/contracts/)

### Week 4 (Days 22–30): Dev Tooling & First Deployment
- [ ] Day 22: Introduction to Hardhat — setup, config, compilation
- [ ] Day 23: Introduction to Foundry — forge, cast, anvil, chisel
- [ ] Day 24: Writing deployment scripts (Hardhat)
- [ ] Day 25: Writing deployment scripts (Foundry)
- [ ] Day 26: Deploying to local testnet (Anvil / Hardhat node)
- [ ] Day 27: Deploy to Sepolia testnet — get test ETH from faucets
- [ ] Day 28: Etherscan verification — verify your contract on-chain
- [ ] Day 29: Introduction to testing — unit tests with Hardhat & Foundry
- [ ] Day 30: **Month 1 Capstone** — Deploy & verify your Crowdfunding contract on Sepolia

**Resources:**
- 🎥 [Cyfrin Updraft — Foundry Fundamentals](https://updraft.cyfrin.io/courses/foundry) — Patrick Collins (FREE)
- 📖 [Hardhat Docs](https://hardhat.org/docs)
- 📖 [Foundry Book](https://book.getfoundry.sh/)
- 🛠️ [Alchemy](https://www.alchemy.com/) — RPC provider
- 🛠️ [Sepolia Faucet](https://sepoliafaucet.com/)

**Month 1 Deliverables:**
- ✅ 2 deployed contracts (Simple Storage + Crowdfunding) on Sepolia
- ✅ Notes on blockchain fundamentals
- ✅ 4 X threads (1 per week)
- ✅ Daily GitHub commits

---

## 🟡 MONTH 2 — Intermediate Solidity & Smart Contract Patterns  
*Apr 20 – May 19 · Days 31–60*

### Week 5 (Days 31–37): ERC Standards & Token Development
- [ ] Day 31: What are ERCs? EIP process, ERC-20 standard deep-dive
- [ ] Day 32: Build an ERC-20 token from scratch
- [ ] Day 33: Build an ERC-20 token using OpenZeppelin
- [ ] Day 34: ERC-721 standard — NFTs, metadata, tokenURI
- [ ] Day 35: Build an ERC-721 NFT contract with on-chain metadata
- [ ] Day 36: ERC-1155 — multi-token standard, batch operations
- [ ] Day 37: **Project** — Deploy your own ERC-20 token + NFT collection on Sepolia

**Resources:**
- 📖 [EIP-20 Standard](https://eips.ethereum.org/EIPS/eip-20)
- 📖 [EIP-721 Standard](https://eips.ethereum.org/EIPS/eip-721)
- 📖 [OpenZeppelin ERC-20 Guide](https://docs.openzeppelin.com/contracts/5.x/erc20)
- 📖 [OpenZeppelin ERC-721 Guide](https://docs.openzeppelin.com/contracts/5.x/erc721)
- 🎥 [Cyfrin Updraft — Advanced Foundry](https://updraft.cyfrin.io/courses/advanced-foundry)

### Week 6 (Days 38–44): Advanced Solidity Patterns
- [ ] Day 38: Design patterns — Factory, Proxy, Singleton
- [ ] Day 39: Upgradeable contracts — Transparent Proxy, UUPS
- [ ] Day 40: Implementing upgradeable contracts with OpenZeppelin
- [ ] Day 41: Library contracts and using `using ... for`
- [ ] Day 42: ABI encoding/decoding — abi.encode, abi.encodePacked, abi.decode
- [ ] Day 43: Low-level calls — delegatecall, staticcall
- [ ] Day 44: **Project** — Build an upgradeable ERC-20 token with proxy pattern

**Resources:**
- 📖 [OpenZeppelin Upgrades](https://docs.openzeppelin.com/upgrades-plugins/)
- 📖 [EIP-1967: Proxy Storage Slots](https://eips.ethereum.org/EIPS/eip-1967)
- 🎥 [Smart Contract Programmer — Proxy Patterns](https://www.youtube.com/watch?v=bdXJmWajZRY)
- 📖 [Solidity Patterns](https://fravoll.github.io/solidity-patterns/)

### Week 7 (Days 45–51): Testing & Debugging Mastery
- [ ] Day 45: Unit testing best practices — Foundry forge test
- [ ] Day 46: Fuzz testing with Foundry
- [ ] Day 47: Invariant testing with Foundry
- [ ] Day 48: Fork testing — forking mainnet in Foundry
- [ ] Day 49: Gas optimization basics — storage packing, memory vs calldata
- [ ] Day 50: Debugging with Tenderly, Foundry traces, console.log
- [ ] Day 51: **Project** — Write comprehensive test suite for your ERC-20 token (>95% coverage)

**Resources:**
- 📖 [Foundry Testing Docs](https://book.getfoundry.sh/forge/tests)
- 📖 [Foundry Fuzz Testing](https://book.getfoundry.sh/forge/fuzz-testing)
- 🎥 [Cyfrin Updraft — Advanced Foundry](https://updraft.cyfrin.io/courses/advanced-foundry)
- 🛠️ [Tenderly](https://tenderly.co/) — debugger & simulator

### Week 8 (Days 52–60): Security Fundamentals
- [ ] Day 52: Common vulnerabilities — reentrancy, integer overflow, front-running
- [ ] Day 53: The DAO hack case study
- [ ] Day 54: Access control vulnerabilities, tx.origin vs msg.sender
- [ ] Day 55: Oracle manipulation & flash loan attacks
- [ ] Day 56: Start Ethernaut challenges (levels 0–5)
- [ ] Day 57: Ethernaut challenges (levels 6–10)
- [ ] Day 58: Ethernaut challenges (levels 11–15)
- [ ] Day 59: Writing a basic audit report
- [ ] Day 60: **Month 2 Review** — Blog post on "Top 10 Smart Contract Vulnerabilities"

**Resources:**
- 🎥 [Cyfrin Updraft — Security & Auditing](https://updraft.cyfrin.io/courses/security) — Patrick Collins (FREE)
- 📖 [SWC Registry](https://swcregistry.io/) — Smart Contract Weakness Classification
- 🛠️ [Ethernaut](https://ethernaut.openzeppelin.com/) — Security CTF
- 📖 [Consensys Smart Contract Best Practices](https://consensys.github.io/smart-contract-best-practices/)
- 📖 [Rekt News](https://rekt.news/) — Hack post-mortems

**Month 2 Deliverables:**
- ✅ ERC-20 Token + NFT Collection deployed
- ✅ Upgradeable proxy contract
- ✅ 15 Ethernaut levels solved
- ✅ 4 X threads + daily commits

---

## 🔵 MONTH 3 — Full-Stack DApp Development  
*May 20 – Jun 19 · Days 61–90*

### Week 9 (Days 61–67): Frontend Basics for Web3
- [ ] Day 61: React.js crash course (if not already known) — components, state, hooks
- [ ] Day 62: Next.js fundamentals — routing, SSR, API routes
- [ ] Day 63: TypeScript essentials for Web3 development
- [ ] Day 64: Introduction to ethers.js v6 — providers, signers, contracts
- [ ] Day 65: Introduction to viem & wagmi — modern Web3 React hooks
- [ ] Day 66: Connecting wallets — MetaMask, WalletConnect, RainbowKit
- [ ] Day 67: **Mini Project** — Build a wallet connection page with balance display

**Resources:**
- 📖 [ethers.js v6 Docs](https://docs.ethers.org/v6/)
- 📖 [wagmi Docs](https://wagmi.sh/)
- 📖 [viem Docs](https://viem.sh/)
- 📖 [RainbowKit Docs](https://www.rainbowkit.com/docs/introduction)
- 🎥 [Cyfrin Updraft — Full-Stack Web3](https://updraft.cyfrin.io/)

### Week 10 (Days 68–74): Building DApp Frontends
- [ ] Day 68: Reading contract state from frontend — useReadContract
- [ ] Day 69: Writing to contracts — useWriteContract, transaction lifecycle
- [ ] Day 70: Handling events — listening, filtering, parsing logs
- [ ] Day 71: IPFS & decentralized storage — Pinata, Filecoin, Arweave
- [ ] Day 72: Uploading NFT metadata to IPFS
- [ ] Day 73: Error handling, loading states, toast notifications
- [ ] Day 74: **Project** — Build an NFT minting dApp (frontend + contract)

**Resources:**
- 📖 [IPFS Docs](https://docs.ipfs.tech/)
- 🛠️ [Pinata](https://www.pinata.cloud/) — IPFS pinning
- 🛠️ [thirdweb](https://thirdweb.com/) — Web3 dev tools
- 📖 [Alchemy University](https://www.alchemy.com/university) — free courses

### Week 11 (Days 75–81): The Graph & Data Indexing
- [ ] Day 75: Why indexing matters — limitations of RPC calls
- [ ] Day 76: The Graph protocol — subgraphs, schema, handlers
- [ ] Day 77: Writing your first subgraph — entities, event handlers
- [ ] Day 78: Deploying a subgraph to The Graph hosted service
- [ ] Day 79: Querying subgraphs with GraphQL from frontend
- [ ] Day 80: Alternatives — Moralis, Alchemy Enhanced APIs, Dune
- [ ] Day 81: **Project** — Add subgraph indexing to your NFT dApp

**Resources:**
- 📖 [The Graph Docs](https://thegraph.com/docs/)
- 🎥 [The Graph Tutorial](https://www.youtube.com/watch?v=tM0DNJdOXSo)
- 📖 [GraphQL Basics](https://graphql.org/learn/)
- 🛠️ [Graph Studio](https://thegraph.com/studio/)

### Week 12 (Days 82–90): Full-Stack DApp Capstone
- [ ] Day 82: Smart contract design for a Token Marketplace
- [ ] Day 83: Implement marketplace contract — list, buy, cancel
- [ ] Day 84: Write comprehensive tests for marketplace
- [ ] Day 85: Deploy marketplace to Sepolia
- [ ] Day 86: Build frontend — listing page, buy flow
- [ ] Day 87: Build frontend — user dashboard, my listings
- [ ] Day 88: Add subgraph for marketplace events
- [ ] Day 89: Polish UI, handle edge cases, optimize UX
- [ ] Day 90: **Month 3 Capstone** — Deploy full-stack NFT Marketplace, write case study

**Resources:**
- 📖 [Scaffold-ETH 2](https://scaffoldeth.io/) — rapid prototyping
- 🎥 [Full-Stack Web3 by Patrick Collins](https://www.youtube.com/watch?v=gyMwXuJrbJQ) (relevant sections)
- 📖 [Chainlink Docs](https://docs.chain.link/) — oracles for price feeds

**Month 3 Deliverables:**
- ✅ NFT Minting dApp (live)
- ✅ Full-Stack NFT Marketplace (live)
- ✅ Subgraph deployed
- ✅ 4 X threads + daily commits

---

## 🟣 MONTH 4 — DeFi Deep Dive  
*Jun 20 – Jul 19 · Days 91–120*

### Week 13 (Days 91–97): DeFi Fundamentals
- [ ] Day 91: DeFi ecosystem overview — TVL, protocols, composability
- [ ] Day 92: Automated Market Makers (AMMs) — Uniswap V2 math (x*y=k)
- [ ] Day 93: Uniswap V2 codebase walkthrough — Factory, Router, Pair
- [ ] Day 94: Uniswap V3 — concentrated liquidity, tick math
- [ ] Day 95: Lending protocols — Aave & Compound architecture
- [ ] Day 96: Stablecoins — algorithmic vs collateralized, DAI, USDC
- [ ] Day 97: **Study** — Write a deep-dive thread on AMM math

**Resources:**
- 📖 [Uniswap V2 Docs](https://docs.uniswap.org/contracts/v2/overview)
- 📖 [Uniswap V3 Whitepaper](https://uniswap.org/whitepaper-v3.pdf)
- 📖 [Aave V3 Docs](https://docs.aave.com/)
- 📖 [Compound Docs](https://docs.compound.finance/)
- 🎥 [Finematics — DeFi Explained](https://www.youtube.com/c/Finematics)
- 📖 [DeFi MOOC](https://defi-learning.org/) — Berkeley

### Week 14 (Days 98–104): Building a DEX
- [ ] Day 98: Design your own AMM — constant product formula
- [ ] Day 99: Implement liquidity pool contract — addLiquidity, removeLiquidity
- [ ] Day 100: 🎉 **Day 100!** — Implement swap function with fee mechanism
- [ ] Day 101: Implement LP token (ERC-20) for liquidity providers
- [ ] Day 102: Write comprehensive tests — edge cases, slippage
- [ ] Day 103: Frontend — swap interface with price impact display
- [ ] Day 104: **Project** — Deploy your DEX to Sepolia

**Resources:**
- 📖 [Uniswap V2 Core Code](https://github.com/Uniswap/v2-core)
- 📖 [Programming DeFi: Uniswap V2](https://jeiwan.net/posts/programming-defi-uniswapv2-1/)
- 🎥 [Smart Contract Programmer — Uniswap](https://www.youtube.com/watch?v=qB2Ulx201wY)

### Week 15 (Days 105–111): Yield, Staking & Flash Loans
- [ ] Day 105: Yield farming mechanics — liquidity mining, reward distribution
- [ ] Day 106: Build a staking contract — stake, unstake, claim rewards
- [ ] Day 107: Implement reward calculation — per-second accrual
- [ ] Day 108: Flash loans — how they work, Aave flash loans
- [ ] Day 109: Build a flash loan receiver contract
- [ ] Day 110: Flash loan arbitrage — theory and implementation
- [ ] Day 111: **Project** — Deploy staking contract with frontend

**Resources:**
- 📖 [Aave Flash Loans](https://docs.aave.com/developers/guides/flash-loans)
- 📖 [Synthetix Staking Rewards](https://github.com/Synthetixio/synthetix/blob/develop/contracts/StakingRewards.sol)
- 🎥 [DeFi Developer Road Map](https://github.com/OffcierCia/DeFi-Developer-Road-Map)

### Week 16 (Days 112–120): DAO & Governance
- [ ] Day 112: DAO concepts — governance tokens, proposals, voting
- [ ] Day 113: OpenZeppelin Governor — architecture overview
- [ ] Day 114: Build a governance token (ERC-20Votes)
- [ ] Day 115: Implement Governor contract — propose, vote, execute
- [ ] Day 116: Timelock controller — delay execution for safety
- [ ] Day 117: Build DAO frontend — proposal creation, voting UI
- [ ] Day 118: Integrate with Tally or Snapshot for governance UI
- [ ] Day 119: Test full governance flow end-to-end
- [ ] Day 120: **Month 4 Capstone** — Deploy DAO with governance on Sepolia

**Resources:**
- 📖 [OpenZeppelin Governor](https://docs.openzeppelin.com/contracts/5.x/governance)
- 📖 [Tally](https://www.tally.xyz/) — governance dashboard
- 📖 [Snapshot](https://snapshot.org/) — off-chain voting
- 🎥 [Cyfrin Updraft — DAO & Governance](https://updraft.cyfrin.io/)

**Month 4 Deliverables:**
- ✅ Custom DEX with AMM (deployed)
- ✅ Staking/Rewards contract (deployed)
- ✅ DAO with governance (deployed)
- ✅ 4 X threads + daily commits

---

## 🔴 MONTH 5 — Advanced Security & Auditing  
*Jul 20 – Aug 19 · Days 121–150*

### Week 17 (Days 121–127): Advanced Vulnerability Patterns
- [ ] Day 121: Reentrancy deep-dive — cross-function, cross-contract, read-only
- [ ] Day 122: Price oracle manipulation attacks (case studies)
- [ ] Day 123: Signature replay, EIP-712 typed signatures
- [ ] Day 124: Front-running & MEV — sandwich attacks, flashbots
- [ ] Day 125: Storage collision in proxies, uninitialized storage
- [ ] Day 126: Denial of Service patterns — gas griefing, block gas limit
- [ ] Day 127: **CTF** — Damn Vulnerable DeFi (challenges 1–5)

**Resources:**
- 🎥 [Cyfrin Updraft — Security & Auditing (Full Course)](https://updraft.cyfrin.io/courses/security)
- 📖 [Trail of Bits — Building Secure Contracts](https://github.com/crytic/building-secure-contracts)
- 📖 [Secureum Bootcamp](https://secureum.substack.com/)
- 🛠️ [Damn Vulnerable DeFi](https://www.damnvulnerabledefi.xyz/)

### Week 18 (Days 128–134): Security Tools & Analysis
- [ ] Day 128: Static analysis with Slither — setup, detectors, custom rules
- [ ] Day 129: Symbolic execution with Mythril
- [ ] Day 130: Formal verification basics — Certora Prover intro
- [ ] Day 131: Fuzzing with Echidna — property-based testing
- [ ] Day 132: Manual audit methodology — checklist, code review, report writing
- [ ] Day 133: Reading real audit reports — Spearbit, Trail of Bits, OpenZeppelin
- [ ] Day 134: **CTF** — Damn Vulnerable DeFi (challenges 6–10)

**Resources:**
- 🛠️ [Slither](https://github.com/crytic/slither) — static analyzer
- 🛠️ [Mythril](https://github.com/Consensys/mythril) — symbolic execution
- 🛠️ [Echidna](https://github.com/crytic/echidna) — fuzzer
- 📖 [Solodit](https://solodit.xyz/) — audit report aggregator
- 📖 [Code4rena](https://code4rena.com/) — competitive audits

### Week 19 (Days 135–141): Gas Optimization
- [ ] Day 135: EVM opcodes — understanding gas costs at the bytecode level
- [ ] Day 136: Storage optimization — packing, SLOAD/SSTORE costs
- [ ] Day 137: Memory vs calldata optimization, function selector ordering
- [ ] Day 138: Yul/inline assembly basics for gas savings
- [ ] Day 139: Batch operations, multicall pattern
- [ ] Day 140: Gas profiling tools — forge snapshot, hardhat-gas-reporter
- [ ] Day 141: **Project** — Optimize one of your previous contracts, document before/after gas

**Resources:**
- 📖 [EVM Opcodes Reference](https://www.evm.codes/)
- 📖 [Huff Language](https://huff.sh/) — low-level EVM
- 🎥 [Yul and Assembly — Cyfrin](https://updraft.cyfrin.io/)
- 📖 [Gas Optimization Tips](https://www.rareskills.io/post/gas-optimization)

### Week 20 (Days 142–150): Competitive Auditing
- [ ] Day 142: Join Code4rena or Sherlock — understand the format
- [ ] Day 143: Study past contest winners — read winning reports
- [ ] Day 144: Participate in a practice contest (Code4rena)
- [ ] Day 145: Damn Vulnerable DeFi (challenges 11–15)
- [ ] Day 146: Capture The Ether — remaining challenges
- [ ] Day 147: Build your own vulnerable contract challenge
- [ ] Day 148: Write a mock audit report for a public protocol
- [ ] Day 149: Submit findings to Code4rena/Sherlock (if live contest available)
- [ ] Day 150: **Month 5 Review** — Publish "My Smart Contract Security Journey" thread

**Resources:**
- 🛠️ [Code4rena](https://code4rena.com/) — competitive audit platform
- 🛠️ [Sherlock](https://www.sherlock.xyz/) — audit marketplace
- 📖 [Immunefi](https://immunefi.com/) — bug bounty platform
- 📖 [Solodit](https://solodit.xyz/) — aggregated audit findings

**Month 5 Deliverables:**
- ✅ All Ethernaut levels completed
- ✅ 15 Damn Vulnerable DeFi challenges solved
- ✅ Mock audit report published
- ✅ Gas-optimized contract with benchmarks
- ✅ 4 X threads + daily commits

---

## 🟠 MONTH 6 — Multi-Chain, L2s & Infrastructure  
*Aug 20 – Sep 19 · Days 151–180*

### Week 21 (Days 151–157): Layer 2 Scaling Solutions
- [ ] Day 151: L2 landscape — rollups, sidechains, validiums
- [ ] Day 152: Optimistic rollups — Optimism, Arbitrum architecture
- [ ] Day 153: ZK rollups — zkSync, StarkNet, Polygon zkEVM
- [ ] Day 154: Deploy contracts on Arbitrum Sepolia
- [ ] Day 155: Deploy contracts on Optimism Sepolia
- [ ] Day 156: Deploy contracts on Base Sepolia
- [ ] Day 157: **Comparison** — Write a thread comparing L2 developer experience

**Resources:**
- 📖 [L2Beat](https://l2beat.com/) — L2 analytics
- 📖 [Arbitrum Docs](https://docs.arbitrum.io/)
- 📖 [Optimism Docs](https://docs.optimism.io/)
- 📖 [Base Docs](https://docs.base.org/)
- 📖 [zkSync Docs](https://docs.zksync.io/)
- 🎥 [Vitalik — Incomplete Guide to Rollups](https://vitalik.eth.limo/general/2021/01/05/rollup.html)

### Week 22 (Days 158–164): Cross-Chain Communication
- [ ] Day 158: Cross-chain bridges — how they work, trust assumptions
- [ ] Day 159: Chainlink CCIP — cross-chain messaging
- [ ] Day 160: LayerZero — omnichain interoperability
- [ ] Day 161: Build a cross-chain token transfer using CCIP
- [ ] Day 162: Wormhole — cross-chain messaging architecture
- [ ] Day 163: Cross-chain security considerations & bridge hacks
- [ ] Day 164: **Project** — Deploy a cross-chain messaging dApp

**Resources:**
- 📖 [Chainlink CCIP Docs](https://docs.chain.link/ccip)
- 📖 [LayerZero Docs](https://docs.layerzero.network/)
- 📖 [Wormhole Docs](https://docs.wormhole.com/)
- 📖 [Bridge hack post-mortems on Rekt](https://rekt.news/)

### Week 23 (Days 165–171): Account Abstraction & Advanced Patterns
- [ ] Day 165: Account Abstraction — ERC-4337 overview
- [ ] Day 166: Smart contract wallets — UserOperation, Bundlers, Paymasters
- [ ] Day 167: Build a simple smart wallet with social recovery
- [ ] Day 168: Gasless transactions — meta-transactions, relayers
- [ ] Day 169: EIP-2612 Permit — gasless token approvals
- [ ] Day 170: Multicall & batch transactions
- [ ] Day 171: **Project** — Build a dApp using account abstraction (gasless minting)

**Resources:**
- 📖 [ERC-4337 Docs](https://www.erc4337.io/)
- 📖 [Alchemy Account Abstraction](https://www.alchemy.com/account-abstraction)
- 📖 [Biconomy Docs](https://docs.biconomy.io/)
- 📖 [ZeroDev Docs](https://docs.zerodev.app/)

### Week 24 (Days 172–180): Advanced Infrastructure
- [ ] Day 172: MEV — Flashbots, PBS, MEV-Boost
- [ ] Day 173: Oracles deep-dive — Chainlink VRF, price feeds, automation
- [ ] Day 174: Decentralized storage — IPFS, Arweave, Filecoin comparison
- [ ] Day 175: ENS — Ethereum Name Service integration
- [ ] Day 176: Push Protocol — decentralized notifications
- [ ] Day 177: The Graph — advanced subgraph patterns
- [ ] Day 178: Intro to Solana — Rust, Anchor framework (awareness)
- [ ] Day 179: Comparing EVM vs non-EVM chains
- [ ] Day 180: **Month 6 Review** — "Multi-chain Developer Guide" blog post

**Resources:**
- 📖 [Flashbots Docs](https://docs.flashbots.net/)
- 📖 [Chainlink VRF](https://docs.chain.link/vrf)
- 📖 [ENS Docs](https://docs.ens.domains/)
- 📖 [Push Protocol Docs](https://docs.push.org/)
- 📖 [Anchor (Solana) Docs](https://www.anchor-lang.com/)

**Month 6 Deliverables:**
- ✅ Contracts deployed on 3+ L2 chains
- ✅ Cross-chain messaging dApp
- ✅ Account abstraction project
- ✅ 4 X threads + daily commits

---

## ⚫ MONTH 7 — Capstone Projects & Open Source  
*Sep 20 – Oct 19 · Days 181–210*

### Week 25–26 (Days 181–194): Capstone Project 1 — DeFi Protocol
- [ ] Days 181–183: Design a full DeFi protocol (lending/borrowing OR DEX aggregator)
- [ ] Days 184–186: Implement core smart contracts
- [ ] Days 187–189: Write comprehensive test suite (unit + fuzz + invariant)
- [ ] Days 190–191: Build production-quality frontend
- [ ] Day 192: Deploy to L2 testnet
- [ ] Day 193: Write documentation & README
- [ ] Day 194: **Ship** — Share on X, tag protocols, request feedback

### Week 27–28 (Days 195–210): Capstone Project 2 + Open Source
- [ ] Days 195–197: Design a unique project (ideas below)
- [ ] Days 198–200: Implement smart contracts
- [ ] Days 201–203: Build frontend & integrate
- [ ] Days 204–206: Deploy, test, document
- [ ] Day 207: Start contributing to open source — OpenZeppelin, Foundry, Uniswap
- [ ] Day 208: Submit your first PR to a Web3 project
- [ ] Day 209: Create developer tools or templates that help others
- [ ] Day 210: **Month 7 Review** — Portfolio case studies for both projects

**Capstone Project Ideas:**
1. **Decentralized Prediction Market** — binary outcomes, oracle resolution
2. **Multi-sig Wallet with Social Recovery** — Gnosis Safe inspired
3. **On-chain Subscription Service** — recurring payments via smart contracts
4. **Decentralized Identity Verification** — soulbound tokens + ZK proofs
5. **Real-time Auction Platform** — English/Dutch auctions on-chain
6. **Cross-chain NFT Bridge** — move NFTs between L2s

**Resources:**
- 📖 [Good First Issues — Web3](https://github.com/nicedoc/awesome-good-first-issues)
- 🛠️ [Scaffold-ETH 2](https://scaffoldeth.io/) — rapid prototyping
- 📖 [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)

**Month 7 Deliverables:**
- ✅ 2 polished capstone projects (deployed, documented, live)
- ✅ 1+ open source PR submitted
- ✅ Portfolio website updated
- ✅ 4 X threads + daily commits

---

## ⚪ MONTH 8 — Job Prep, Networking & Launch  
*Oct 20 – Nov 19 · Days 211–240*

### Week 29 (Days 211–217): Portfolio & Online Presence
- [ ] Day 211: Polish GitHub profile — pinned repos, professional README
- [ ] Day 212: Build/update portfolio website showcasing Web3 projects
- [ ] Day 213: Write technical blog posts on Mirror/Medium/Hashnode
- [ ] Day 214: Create a "What I Built in 8 Months" mega-thread
- [ ] Day 215: Record Loom/video walkthroughs of your best projects
- [ ] Day 216: Update LinkedIn with Web3 skills, projects, certifications
- [ ] Day 217: Gather testimonials from open source contributions

**Resources:**
- 🛠️ [Mirror](https://mirror.xyz/) — decentralized blogging
- 🛠️ [Hashnode](https://hashnode.com/) — developer blog
- 📖 [GitHub Profile README Generator](https://rahuldkjain.github.io/gh-profile-readme-generator/)

### Week 30 (Days 218–224): Interview Preparation
- [ ] Day 218: Solidity interview questions — top 50, practice answers
- [ ] Day 219: EVM & blockchain concept questions
- [ ] Day 220: System design for Web3 — DEX, lending protocol, NFT marketplace
- [ ] Day 221: Live coding practice — build a contract in 30 min
- [ ] Day 222: Behavioral interview prep — STAR method, Web3 motivation
- [ ] Day 223: Mock interview with a friend or AI
- [ ] Day 224: Review and refine weak areas

**Resources:**
- 📖 [Web3 Interview Questions](https://www.rareskills.io/post/solidity-interview-questions)
- 📖 [Blockchain Interview Questions](https://www.web3.career/learn-web3/top-blockchain-interview-questions)
- 📖 [Smart Contract Engineer Interview Guide](https://github.com/tamjid0x01/SmartContracts-audit-checklist)

### Week 31 (Days 225–231): Networking & Community
- [ ] Day 225: Join Web3 Discord communities — Ethereum, Chainlink, Alchemy
- [ ] Day 226: Attend virtual hackathons — ETHGlobal, Devfolio
- [ ] Day 227: Connect with 10 Web3 developers on X/LinkedIn daily
- [ ] Day 228: Engage meaningfully in governance forums
- [ ] Day 229: Apply to Web3-specific job boards
- [ ] Day 230: Reach out to hiring managers / founders directly
- [ ] Day 231: Attend local Web3 meetups or conferences

**Resources:**
- 🛠️ [ETHGlobal](https://ethglobal.com/) — hackathons
- 🛠️ [Devfolio](https://devfolio.co/) — hackathons
- 🛠️ [Web3.career](https://web3.career/) — job board
- 🛠️ [CryptoJobsList](https://cryptojobslist.com/) — job board
- 🛠️ [Superteam](https://superteam.fun/) — community & bounties

### Week 32 (Days 232–240): Apply & Launch
- [ ] Day 232: Tailor resume for each application — highlight projects
- [ ] Day 233: Apply to 5 positions daily — internships & junior roles
- [ ] Day 234: Apply to Web3 bounty programs — Gitcoin, Immunefi, Superteam
- [ ] Day 235: Follow up on applications, schedule interviews
- [ ] Day 236: Continue building in public — X posts, GitHub activity
- [ ] Day 237: Take on freelance/bounty work to build real-world experience
- [ ] Day 238: Reflect on the journey — what worked, what didn't
- [ ] Day 239: Plan next steps — specialization, advanced topics
- [ ] Day 240: **🎉 DAY 240 — GRADUATION** — Publish final retrospective thread

**Job Boards & Platforms:**
- 🛠️ [Web3.career](https://web3.career/)
- 🛠️ [CryptoJobsList](https://cryptojobslist.com/)
- 🛠️ [Remote3](https://remote3.co/)
- 🛠️ [Wellfound (AngelList)](https://wellfound.com/)
- 🛠️ [Gitcoin](https://gitcoin.co/) — grants & bounties
- 🛠️ [Immunefi](https://immunefi.com/) — bug bounties
- 🛠️ [Superteam](https://superteam.fun/) — Solana ecosystem bounties

**Month 8 Deliverables:**
- ✅ Polished portfolio with 5+ deployed projects
- ✅ 20+ job applications submitted
- ✅ Interview-ready with mock practice
- ✅ Active online presence with 240 days of public building
- ✅ Final retrospective thread

---

## 📊 Progress Tracking

| Month | Status | Key Milestone |
|-------|--------|---------------|
| 1 | ⬜ Not Started | First contract deployed |
| 2 | ⬜ Not Started | ERC-20 token + 15 Ethernaut levels |
| 3 | ⬜ Not Started | Full-stack NFT Marketplace |
| 4 | ⬜ Not Started | Custom DEX + DAO deployed |
| 5 | ⬜ Not Started | Mock audit report + CTF mastery |
| 6 | ⬜ Not Started | Multi-chain + Account Abstraction |
| 7 | ⬜ Not Started | 2 capstone projects shipped |
| 8 | ⬜ Not Started | Job-ready, 20+ applications |

---

*"The best time to start was yesterday. The second best time is now." — Start today, ship daily.*
