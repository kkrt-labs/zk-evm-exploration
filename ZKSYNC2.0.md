## zkSync 2.0

zk-Sync is a Layer 2 scaling solution for the Ethereum network that utilizes zero-knowledge proofs to increase its transaction processing capacity. It allows for faster and cheaper transactions while preserving the privacy of transactions and data. The zk-EVM, a virtual machine built on top of zk-Sync, runs smart contracts and ensures their secure and verifiable execution. zk-Sync is aimed to address the scalability limitations of the Ethereum network, making it a promising solution for decentralized applications.

![1_ISUd6Kri7-RpwaQU-S1qQA](https://user-images.githubusercontent.com/11755605/216637651-6d3159f4-6fc7-41ef-9557-c11158cff2b4.png)

## Programming language to code the VM:
* Rust

## Type of zk technology used for proving computation (SNARK, STARK, etc.)
* SNARK

## zkEVM type (1, 2, 3 or 4)
* 4

## How many people are approx. in the team (e.g. no. of GitHub contributors)
* 50

## Time of inception (first commit)
* Nov 19, 2018 
https://github.com/matter-labs/zksync/commit/f635e252c26b1c4d3b8e913ecb96e24fb58bc28d

## Type of stack used for networking and consensus (single sequencer? single prover? open sourced?)

## Testnet ready? Open? Beta, Alpha? 
* Baby alpha

## Date (if any) of production readyness
* May 31, 2021 Alpha

## Team leader prior experience, if any (e.g. Jordi Baylina for Polygon zkEVM coinvented circom2)
* Alex Gluchowski

## Diagram

![0_S3TKmlfGRTx5MNkE](https://user-images.githubusercontent.com/11755605/216640246-0b57ef00-5669-4442-beb1-fa60108c5b81.png)

## How ZK EVM compiler work?
The zk-Sync zk-EVM compiler is responsible for compiling smart contracts written in high-level programming languages into a format that can be executed on the zk-EVM. The compiler takes the source code of a smart contract as input and produces machine-readable code in the form of bytecode that can be executed on the zk-EVM.

The compiler works by first converting the source code into LLVM intermediate representation (IR). This IR is then optimized for the target platform and architecture, which in the case of zk-Sync is the zk-EVM. The optimized IR is then translated into bytecode, which can be executed on the zk-EVM.

The bytecode produced by the compiler is then used to deploy the smart contract on the Ethereum blockchain, where it can be executed by users and other smart contracts. The zk-EVM ensures that the execution of the smart contract is secure, transparent, and verifiable, using zero-knowledge proofs.

Overall, the zk-Sync zk-EVM compiler is a critical component of the zk-Sync platform, as it allows developers to write smart contracts in high-level programming languages and deploy them on the Ethereum blockchain, while ensuring their secure and verifiable execution on the zk-EVM.







## Resources
https://blog.matter-labs.io/zksync-2-0-hello-ethereum-ca48588de179

https://docs.zksync.io/dev/

https://github.com/matter-labs/zksync/blob/master/docs/architecture.md

https://vitalik.ca/general/2022/08/04/zkevm.html

