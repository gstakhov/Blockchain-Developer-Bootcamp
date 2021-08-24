## Other Security Options

Outside of the tools we've provided so far, there are other great security analysis tools:

## Tools
- <a href="https://openzeppelin.com/defender/" target="_blank" rel="noopener noreferrer">OpenZeppelin Defender</a> Less of a security tool per se and more like an operating system or dashboard for your smart contracts. This allows you to monitor your smart contracts, respond to exploits or bugs by adjusting access control, and private transaction relayers.
- <a href="https://github.com/crytic/slither" target="_blank" rel="noopener noreferrer">Sliter</a> A static analysis framework for Solidity built by the auditing firm <a href="https://www.trailofbits.com/" target="_blank" rel="noopener noreferrer">Trail of Bits.</a> It is written in Python, is open-source and you can read more about it <a href="https://blog.trailofbits.com/2018/10/19/slither-a-solidity-static-analysis-framework/" target="_blank" rel="noopener noreferrer">here.</a> 
- <a href="https://github.com/trailofbits/manticore" target="_blank" rel="noopener noreferrer">Manticore</a> "A <a href="https://en.wikipedia.org/wiki/Symbolic_execution" target="_blank" rel="noopener noreferrer">symbolic execution</a> tool for analysis of smart contracts and binaries" as well as WASM modules. Also built by Trail of Bits! <a href="https://blog.trailofbits.com/2017/04/27/manticore-symbolic-execution-for-humans/" target="_blank" rel="noopener noreferrer">Read more here.</a>
- <a href="https://github.com/crytic/ethersplay" target="_blank" rel="noopener noreferrer">Ethersplay</a> An EVM Disassembler which takes as input raw EVM bytecode (your contract you're deploying) and analyzes it at the Assembly level. It can provide a flow graph of all the functions in the bytecode. *Another* tool from Trail of Bits, it also can let you know where Manticore has scanned.
- <a href="https://github.com/crytic/echidna" target="_blank" rel="noopener noreferrer">Echidna</a> A fuzzer like Scribble. It is "a Haskell program designed for fuzzing/property-based testing of Ethereum smarts contracts. It uses sophisticated grammar-based fuzzing campaigns based on a contract ABI to falsify user-defined predicates or Solidity assertions." (<a href="https://github.com/crytic/echidna" target="_blank" rel="noopener noreferrer">source</a>) Also from Trail of Bits.

## Learning
- <a href="https://github.com/openblocksec/blocksec-ctfs" target="_blank" rel="noopener noreferrer">Blocksec CTFs</a> An amazing collection of blockchain Capture The Flag (CTF) exercises and write-ups
- <a href="https://swende.se/blog/Ethereum_quirks_and_vulns.html" target="_blank" rel="noopener noreferrer">Article: Ethereum Quirks and Vulnerabilities</a> Discussion around attack vectors on Ethereum
- <a href="https://ethernaut.openzeppelin.com/" target="_blank" rel="noopener noreferrer">Ethernaut</a> Phenomenal CTF / Wargame series of exercises for blockchain security. Be sure to checkout the <a href="https://twitter.com/ethernautdao?lang=en" target="_blank" rel="noopener noreferrer">EthernautDAO,</a> organized in part by the designing of Ethernaut.
- <a href="https://www.damnvulnerabledefi.xyz/" target="_blank" rel="noopener noreferrer">DamnVulnerableDeFi</a> A DeFi-oriented CFT
- <a href="https://capturetheether.com/" target="_blank" rel="noopener noreferrer">Capture the Ether</a> Another blockchain CTF, written by <a href="https://twitter.com/smarx" target="_blank" rel="noopener noreferrer">Steve Marx</a>
- <a href="https://ciphershastra.com/" target="_blank" rel="noopener noreferrer">CipherShastra</a> Another CTF-style learning challenge
- <a href="https://consensys.net/diligence/audits/" target="_blank" rel="noopener noreferrer">Diligence Public Audits,</a> <a href="https://blog.openzeppelin.com/security-audits/" target="_blank" rel="noopener noreferrer">OpenZeppelin Audits</a> Another great way to learn to audit is to read reports from the best organizations doing them. Trail of Bits is not blockchain-specific, but you can see <a href="https://github.com/trailofbits/publications#security-reviews" target="_blank" rel="noopener noreferrer">their public security "reviews" here.</a>

## Audits
- <a href="https://mobile.twitter.com/tinchoabbate/status/1400170232904400897?s=20" target="_blank" rel="noopener noreferrer">Thread: Before an Audit</a> @Tincho, a security researcher at OpenZeppelin, walks through the things you absolutely should do before submitting your code for an audit
- <a href="https://code423n4.com/" target="_blank" rel="noopener noreferrer">Code 423n4</a> "A community-driven approach to competitive smart contract audits." A great way to get into auditing — no experience necessary.
- <a href="https://immunefi.com/" target="_blank" rel="noopener noreferrer">Immunefi</a> A collection of bug bounties for blockchain projects anyone can contribute.
- <a href="https://blog.coinbase.com/introducing-solidify-a-tool-to-automatically-detect-and-classify-smart-contract-security-risks-73a1338fdbbe" target="_blank" rel="noopener noreferrer">Article: Introducing Solidify (Coinbase)</a> We haven't gotten a chance to try this one, but Coinbase offering a new tool for smart contract analysis. This is not an endorsement of this, just letting you know it exists!