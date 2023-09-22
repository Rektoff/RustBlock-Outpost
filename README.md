# RustBlock Developer Knowledge Base


Here [Rektoff](https://twitter.com/rektoff_xyz) core team presents a knowledge base and market environment overview about the Rust blockchain development ecosystem. We saw a demand in the last months and got a lot of requests to create something related. So here it is! 

Any help would be rewarded soon. Let's build a foundation of new rustecean-based applications in blockchain field!

Main Contributors: [yehor b.], [officercia], [jared],

<h5>Disclaimer<h5>

The information shared below is an addition to our RustBlockSec article that you can check here - [Tap!](https://mirror.xyz/0xc34B1730BA53abD717a1E57A358F39C046053581/DLhgR1FqmKdTZyzxilIzykRCIGzEe0lgkhf6VYvnv-E)

--------


**Recent Big News:**

- [Aztec Network shared an update](https://x.com/aztecnetwork/status/1702338983999799374?s=20) about the launch of a new smart contract framework for their ecosystem-native Noir language, which has 99% syntax similarity to Rust.
  
- [Offchain Labs shared an update](https://x.com/OffchainLabs/status/1697232795268177987?s=20) about the launch of an official testnet for their newcome **Rust**, C, C++ smart-contract implementation for Arbitrum L2.

- [Paradigm's R&D team released](https://x.com/gakonst/status/1671186635814473728?s=20) a new alpha version of Reth built purely in Rust. That is a [great contribution](https://clientdiversity.org/) towards Ethereum decentralization and performance + first [big rust dev conference](https://www.youtube.com/watch?v=aFk0WymgAo8) where they broadly introduced the audience to Foundry 2.0, Rivet, Alloy, Ruint and other Rust-related innovative tools for Ethereum.

- Funded in July with [40m$ in series A](https://www.risczero.com/news/series-a), start-up RiscZero presented [Zeth and RiscZero zkEVM](https://www.risczero.com/news/zeth-release), which built using Rust-based tools(revm, ethers, alloy).

![Untitled design(6)](https://github.com/Rektoff/RustBlockSec/assets/144442822/4fbcc71b-48b1-4632-921d-85f9ae71a4d7)

--------

| Navigation | Sections|
|-----:|-----------|
|     1| Smart Contracts|
|     2| Tools |
|     3| Infrastructure |
|     4| Testing/Fuzzing |
|     5| Cryptography/ZK |
|     6| Additional links |



---------

Create and deploy your **smart contracts** using these Rust-inspired platforms/languages/frameworks.

- [Leo](https://github.com/AleoHQ/leo) (Aleo)
- [Noir](https://github.com/noir-lang/noir) (Aztec ZkRollup)
- [Ink!](https://github.com/paritytech/ink) (Polkadot)
- [Sway](https://github.com/FuelLabs/sway) (Fuel Labs)
- [CosmWasm](https://github.com/CosmWasm/cosmwasm) (Cosmos)
- [Stylus](https://github.com/OffchainLabs/stylus) (Arbitrum)
- [Cairo](https://github.com/starkware-libs/cairo) (Starknet/Starkware)
- [Substrate](https://github.com/paritytech/substrate) (Polkadot)
- [Huff](https://github.com/huff-language/huffc) (Ethereum)
- [Rusk](https://github.com/dusk-network/rusk) (Dusk Network)
- [Fe](https://github.com/ethereum/fe) (Ethereum)
- [Mx-SDK](https://github.com/multiversx/mx-sdk-rs) (MultiverseX)
- [NearSDK](https://github.com/near/near-sdk-rs) (NEAR)
- [SolanaToolkit](https://docs.solana.com/developing/on-chain-programs/developing-rust) (Solana)
- [SecretToolkit](https://github.com/scrtlabs/secret-toolkit) (Secret Network)
- [Anchor](https://github.com/coral-xyz/anchor) (Solana)
- [PolkadotSDK](https://github.com/paritytech/polkadot-sdk) (All-in Polkadot)
- [OasisSDK](https://github.com/oasisprotocol/oasis-sdk) (Oasis Protocol)
- [Scrypto](https://github.com/radixdlt/radixdlt-scrypto) (Radix Defi)
- [ConcRustFramework](https://github.com/Concordium/concordium-rust-smart-contracts) - (Concordium)
  
--------

**Tools:**

- [Optimism-rs](https://github.com/refcell/optimism-rs) - Optimism implementation written in Rust(non-official version)
- [Rivet](https://github.com/paradigmxyz/rivet) - browser extension that enables developers to inspect, debug, modify, and manipulate the state of Ethereum
- [Alloy](https://github.com/alloy-rs) - high-performance, well-tested & documented libraries for interacting with Ethereum and other EVM-based chain
- [OrgaTendermint](https://github.com/turbofish-org/orga) - state engine framework powered by Tendermint consensus
- [Sothis](https://github.com/rainshowerLabs/sothis) - tool for replaying historical state on a local anvil/hardhat testnet node
- [Blutgang](https://github.com/rainshowerLabs/blutgang) - load balancer designed with Ethereum's json-rpc 
- [Hyperledger Solang](https://github.com/hyperledger/solang) - solidity compiler for Solana&Polkadot
- [DIDKit](https://github.com/spruceid/didkit) - DID toolkit written in Rust

--------

**Infrastructure:**

- [Reth](https://github.com/paradigmxyz/reth) - fresh rust-based Ethereum execution client by Paradigm team
- [Revm](https://github.com/bluealloy/revm) - Rust Ethereum Virtual Machine
- [Ethers-rs](https://github.com/gakonst/ethers-rs) - eth&celo Rust library
- [Artemis](https://github.com/paradigmxyz/artemis) - framework for writing MEV bots in Rust
- [LightHouse](https://github.com/sigp/lighthouse) - Ethereum Consensus client by Sigma Prime
- [Trin](https://github.com/ethereum/trin) - Portal Network client implementation
- [Zebra](https://github.com/ZcashFoundation/zebra) - consensus-compatible ZCash node
- [Hermes](https://github.com/informalsystems/hermes) - rust-based IBC relayer 
- [Tendermint-rs](https://github.com/informalsystems/tendermint-rs) - blockchain consensus engine for Byzantine fault tolerant applications 
- [VeilidCoDC](https://veilid.com/) - p2p application network by (x_X)
- [Rustlibp2p](https://github.com/libp2p/rust-libp2p) - modular peer-to-peer networking framework
- [ZkSyncSDK](https://docs.zksync.io/api/sdk/rust/tutorial/#adding-dependencies) - ZkSync Rust SDK
- [TezonSmartRollup](https://docs.rs/tezos-smart-rollup/latest/tezos_smart_rollup/) + [Kernel Gallery](https://gitlab.com/tezos/kernel-gallery) - smart rollups on top of Tezos using Rust.
- [StarkNetRust](https://github.com/FuzzingLabs/starknet_in_rust) - Starknet library in Rust
- [Gotham](https://github.com/ZenGo-X/gotham-city/tree/master/) - client/server application for issuing two party ECDSA signatures
  

--------

**Testing&Fuzzing**

- [Foundry 2.0](https://github.com/foundry-rs/foundry) - modular toolkit for ethereum development and testing 
- [Circomspect](https://github.com/trailofbits/circomspect) - static analyzer for Circom ZK framework 
- [Caracal](https://github.com/crytic/caracal) - static analyzer for Starknet smart contracts
- [Cairo-Fuzzer](https://github.com/FuzzingLabs/cairo-fuzzer) - smart contracts fuzzer for Cairo by Fuzzing Labs
- [Fzero-Fuzzer](https://github.com/FuzzingLabs/fzero_fuzzer) - grammar-based fuzzer for Rust
- [WASMRuntimeFuzz](https://github.com/FuzzingLabs/wasm_runtimes_fuzzing) - WebAssembly Runtimes fuzzing 
- [Dylint](https://github.com/trailofbits/dylint/tree/master) - Static Analyzer tool
  

--------

Cryptography&Zero-Knowledge

- [ZkCrypto](https://github.com/zkcrypto) / [bellman](https://github.com/zkcrypto/bellman) - crate for building zk-SNARK circuits
- [ark-gro16](https://github.com/geometryresearch/groth16) -library for designing and working with zero knowledge succinct non-interactive arguments 
- [Boojum](https://github.com/matter-labs/era-boojum) - high-performance proof system for radical decentralization by ZkSync Era
- [Plonky2Starky](https://github.com/mir-protocol/plonky2) - Zk scailing by mir&polygon
- [ZKWASM](https://github.com/xonoxitron/zk-wasm) - ZkWASM written in Rust
- [RustCrypro](https://github.com/RustCrypto) / [EllipticCurves](https://github.com/RustCrypto/elliptic-curves) - General purpose EllipticCC support
- [ZkSnarksSubstrate](https://brightinventions.pl/blog/zk-snarks-in-substrate-part-1/) - ZkNARKs in Substrate framework
- [BulletProofs](https://github.com/dalek-cryptography/bulletproofs) - [non-interactive ZKPs](https://crypto.stanford.edu/bulletproofs/) implementation 
- [Curve25519](https://github.com/dalek-cryptography/curve25519-dalek) - pure-Rust crates for elliptic curve cryptography.
- [Circom](https://github.com/iden3/circom) - domain-specific language for defining arithmetic circuits that can be generated by ZKPs.
- [Zeth](https://github.com/risc0/zeth) - open-source ZK block prover for Ethereum built on the RISC Zero zkVM
- [Spartan](https://github.com/microsoft/Spartan) - 0k proof system by microsoft
- [Zk-Paillier](https://github.com/ZenGo-X/zk-paillier) - paillier(zengoX) zk library
- [BLS](https://github.com/ZenGo-X/multi-party-bls) - MPBls
- [ZkEvm circuits](https://github.com/privacy-scaling-explorations/zkevm-circuits) - exploration focused zk evm circuits
- [MPZ](https://github.com/privacy-scaling-explorations/mpz) - rustecean multi-party computation libraries
- [Arkworks](https://github.com/arkworks-rs) - Rust ecosystem for ZKSnark development
- [LambdaStarkPlatinum](https://github.com/lambdaclass/lambdaworks_stark_platinum) - STARK Prover
  

--------

Additional links:

- [Alchemy Dev Report q2 2023](https://www.alchemy.com/blog/web3-developer-report-q2-2023)
- [Alchemy Dev Report q1 2023](https://www.alchemy.com/blog/web3-developer-report-q1-2023)
- [JetBrains Developer Ecosystem](https://blog.jetbrains.com/rust/2023/01/18/rust-deveco-2022-discover-recent-trends/)
- [GitHub blog about Rust](https://github.blog/2023-08-30-why-rust-is-the-most-admired-language-among-developers/)
- [StackOverFlow Survey 2023](https://survey.stackoverflow.co/2023/#technology)
- [Interview with Senior Rust Developer](https://youtu.be/TGfQu0bQTKc?si=jVeH6HkL78fq2fI3)


```
                                                                                                                                                                                                                                                                                       
                                                                      ...........                                                                                                                                                                                                                           
                                                                    ,xkOOOOOO00OOkxol:;'..                                                                                                                                                                                                                  
                                                                    ;0XXXXXXXXXXXXXXXXXK0Oxl;.                                                                                                                                                                                                              
                                                        ...         ;0XXXXXXXXXXXXXXXXXXXXNNNKx:.                                                                                                                                                                                                           
                                                      .:k00Oxc.     ;KXXXXXXXXXXXXXXXXXXXXXXXNWN0l.                                                                                                                       .'.   .,,.   ...                                                                  
                                                     ;xKXXXNWW0l.   ;0XXXXXXXKOO0KKXXXXXXXXXXXXNWW0c.                                                                                                               .'.. .,cc,.':cc;'.;cc,. ..'.                                                            
                                                   ,xKXXXXXXXNWW0:. ;0XXXXXXXkc:::;:oOXXXXXXXXXXNWMNx.                                                                                                              ,cc:,;cccccccccccccccc;,:cc'                                                            
                                                  .c0XXXXXXXXXXNWKl.cKXXXXXXX0o:;'   .:kXXXXXXXXXNWMWO'                                                                                                       .,:,',:cccccccccccccccccccccccccc;'',:,                                                       
                                                    'o0XXXXXXXXXNNKdxKXXXXXXXKkl;'     .c0XXXXXXXXNWWWO'                                                                                                      .;cccccccccccccccccccccccccccccccccccc;.              ...                                     
                                                      'd0XXXXXXXXXXK0XXXXXXXXXKx:'       ;OXXXXXXXXXNNXo.                                                                                   ',.           ';,,;:cccccccccccccccccccccccccccccccccccc:,,;;'        .;:c'   .'.                               
                                                        ,dKXXXXXXXXXXXXXXXXXXNN0o,        cKXXXXXXXXKKKO,                                                                              ',.  'cc;.         'cccccccccccccccccccccccccccccccccccccccccccccc'      .,cccc.  .,:'                               
                                                          ,dKXXXXXXXXXXXXXXXXNWNk,        .kXXXXXXXX0O0Oc                                                                             'cc,. .:ccc'    ....,cccccccccccccccccccccccccccccccccccccccccccccc,....  'ccccc. .;cc.                               
                                                           .;xKXXXXXXXXXXXXXXNWWKl........,xXXXXXXXX0kkkc.                                                                           .;ccc;..:ccc:.   ,cccccccccccccccccccccccccccccccccccccccccccccccccccccc'  'ccccc:;ccc,.                               
                                             .:ccccclllllooookKXXXXXXXXXXXXXXNNNXK0O000000KXXXXXXXXX0kxxc.                                        .      .                            .;ccc:::ccc;.   .;cccccccccccccccccccccccccccccccccccccccccccccccccccc;.  .,ccccccc:'                                 
                                             ;0XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX0kxxc.                                       :kx,  'xO:                            .';cccccc:...'';:cccccccccccccccccccccccccccccccccccccccccccccccccccc:,''..,cccc:'.                                  
                                             ;0XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX0kxxc.                                       .oX0do0Xo.                               .';cc:'  'cccccccccccccccccccccldOo'.,:ccccccdkd,.;cccccccccccccccccc:'.,c:,.                                     
                                             ;0XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX0kxxc.                                        .xWMMWk.                                   ':c;'..,cccccccccccccccccccclOWK;  .:ccc:;xWK, .;cccccccccccccccc:,,:c;.                                       
                                             ,OKKKKKKKK0000000XXXXXXXXXXXXXXXXXXXXXX0Okxddoooooollllc:cl;                                         cKKkkKXc                                    ..;:c::ccccccccccccccccccc:',l:.  .;ccc:.'c;.  'ccccccccccccccccccc:'                                         
                                              .',,,,,'''''.':kKXXXXXXXXXXXXXXXXXXXXXKOdc,.                                                       cK0; .;KXc                                     .,ccccccccccccccccccccccc,.     .:cccc'     .,ccccccccccccccccccc:,.                                        
                                                          .cOXXXXXXXXXXXXXXXXXXXXXXXXXX0xc'.                                                     ',.    .,'                                    .;ccc:;;:::cccccccccccccccc:,..',:cccccc;''',:ccccccccccccc:;;;::cccc,.                                      
                                                        .:kXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXKOl'                                                                                                  .:ccc;..'''',;:::ccccccccccccccccc;'..';ccccccccccccc::;;,....'..;cc:'                                       
                                                       ;xKXXXXXXXXKkOXXXXXXXXOk0XXXXXXXXXXNX0d,                                                                                                 .,:cc'.....  ....',;;;::::ccccccc;'..,:cccc::::;;,,'...    ... .:c;.                                        
                                                     ,dKXXXXXXXXXOl;oKXXXXXXXkccx0XXXXXXXXXXNNKx;.                                                                                                .,:c,. ..          .........''''''''''........           .. .;c,.                                         
                                                   'o0XXXXXXXXXOo;',oKXXXXXXXOl;;:oOXXXXXXXXXXNWNOl.                                                                                                .,:;.  .                                              .  .,:'                                           
                                                  .lKXXXXXXXX0d:,''.cKXXXXXXX0o:;'..l0XXXXXXXXXNNWWKl.                                                                                                .,;.                                                   ',.                                            
                                                    ,xKXXXX0d:,''.  ;KXXXXXXX0dc;'   .o0XXXXXXXXXNNWW0l.                                                                                                .'.                                                 .'.                                             
                                                      ;xKKxc,''..   ;KXXXXXXX0xl;'     'o0XXXXXXXXXXK00x,                                                                                                 .                                                 .                                               
                                                       .,,.....     ;KXXXXXXX0xo:'       'o0XXXXXXXX0xxxc.                                                                                                                                                                                                  
                                                                    ;KXXXXXXX0xdc'         'o0XXXXXX0xxxc.                                                                                                                                                                                                  
                                                                    ,xOOOOOOkxddl'           'cloooolcll;                                                                                                                                                                                                   
                                                                     .............                                                                                                                                                                                                                          
                                                                                                                                                                                                                                                                                                            
                                                                                                                                                                                                                                                                                     

                          
     
```
