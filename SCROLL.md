![logo_with_text 7c6cafcac81093d6f83b](https://user-images.githubusercontent.com/32202283/216722027-41498295-8290-4937-a047-5c457e2a360f.png)

# Scroll

[Main documentation found at](https://guide.scroll.io/)

Scroll is a zkEVM-based zkRollup on Ethereum that enables native compatibility for existing Ethereum applications and tools.

The Scroll zkEVM is a **Type 2** zkEVM
Smart contracts are written in **Solidity**

The testnet is open, in "pre-alpha" stage. Their L1 and L2's RPC are a subdomain of scroll.io. The Pre-Alpha was released on 2022-07-19, after one year of building, and upgraded three months later on 2022-10-09

Consensus algorithm -> PoA Proof of Authority

### Synthetised zkEVM transaction flow
![oLlyhIx](https://user-images.githubusercontent.com/32202283/216723883-eb0d05c0-8323-4b91-a14e-a134a3b4d5ad.png)
![Sajm1E2](https://user-images.githubusercontent.com/32202283/216723893-4ada47fe-7fbe-4a0f-b2d5-64bba7c916ad.png)

**More informations on this youtube video**
[![Watch the video](https://img.youtube.com/vi/1bVe77-yfBA/hqdefault.jpg)](https://www.youtube.com/watch?v=1bVe77-yfBA&t=879s)

### Here are the connection informations.
---
| Network name       | Scroll L1 Testnet                 | Scroll L2 Testnet                 |
|--------------------|-----------------------------------|-----------------------------------|
| RPC URL            | https://prealpha-rpc.scroll.io/l1 | https://prealpha-rpc.scroll.io/l2 |
| Chain ID           | 534351                            | 534354                            |
| Currency Symbol    | TSETH                             | TSETH                             |
| Block Explorer URL | https://l1scan.scroll.io/         | https://l2scan.scroll.io/         |

## Backend language
Mainly Rust 🦀

The first commit was made on June 29th 2021, which coincides with what is said in the launch blog post ("After one year of working", the post was published on July 19th 2022).

The 3 co-founders are listed in the team section of the website. There are 17 people who did more than 10 commits on the repo, and 55 total contributors. The LinkedIn profile of Scroll lists 30 employees. Also, they follow 28 people on Twitter. Based on that info we can infer that there are 20±5 devs in a team of ~30.

As Scroll is Solidity powered zkEVM, generated opcode is classic Solidity opcode. No specificity there.

### Type of zk technology used for proving computation (SNARK, STARK, etc.)
SNARK

### Type of stack used for networking and consensus (single sequencer? single prover? open sourced?)
Single sequencer, single prover

### Date (if any) of production readiness
Sometime in 2023, according to their discord :

![Wen mainnet](assets/scrollprodready.png "Wen mainnet")

### Diagrams

### Core Team
### Sandy Peng : 
- Experience :  
    ![PengXP](assets/peng1.png "Peng experience")
- Education :  
    ![PengEdu](assets/peng2.png "Peng education")

### Haichen Shen : 
- Worked at Amazon Web Services as a senior applied scientist on AI compilers. Received his Ph.D. in computer science from University of Washington, advised by Professor Arvind Krishnamurthy and Matthai Philipose. Received his bachelor degree in computer science from Institute for Theoretical Computer Science at Tsinghua University.
- Published a few papers, mainly in NN 
- Experience :  
    ![ShenXP](assets/shen1.png "Shen experience")
- Education :  
    ![ShenEdu](assets/shen2.png "Shen education")

### Ye Zhang
- Experience :  
    ![ZhangXP](assets/zhang1.png "Zhang experience")
- Education :  
    ![ZhangEdu](assets/zhang2.png "Zhang education")

### Resources
---
[Pre-Alpha Testnet User Guide](https://guide.scroll.io/)  
[Ground Up Guide: zkEVM, EVM Compatibility & Rollups](https://immutablex.medium.com/ground-up-guide-zkevm-evm-compatibility-rollups-787b6e88108e)  
[Scroll medium article about their application flow](https://scroll-zkp.medium.com/scroll-a-layer-2-ecosystem-based-on-zk-rollup-186ff0d764c)
