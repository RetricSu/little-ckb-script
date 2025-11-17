# Little CKB Script

A curated collection of small on-chain script demos for the CKB (Common Knowledge Base) blockchain. This project aims to showcase and educate developers on writing smart contracts and scripts for CKB, with a focus on simplicity and accessibility.

Most scripts are written in JavaScript using [ckb-js-vm](https://github.com/nervosnetwork/ckb-js-vm), which lowers the barrier to entry by allowing developers to write CKB scripts in a familiar language without needing to learn Rust or other low-level languages.

## List

### Lock

- [hash-lock](https://github.com/nervosnetwork/docs.nervos.org/tree/develop/examples/dApp/simple-lock): a simple hash-lock script that can be unlocked by providing a preimage
- [simple-htlc](https://github.com/RetricSu/simple-htlc): a simple htlc script that can be unlocked by providing a preimage or a timeout refund.
- [spilman-payment](https://github.com/HappySonnyDev/SpilmanPayment): a Spilman payment channel implemented on CKB, used in AI large-model streaming payment scenarios.
- [join-airdrop](https://github.com/RetricSu/join-airdrop): a simple airdrop-lock contract that requires users to join first in order to get airdrop for a specific UDT token so that the minimal-cell providing problems can be solved.

### Type

- [merkle-point](https://github.com/RetricSu/merkle-point): a simple type script that implement a basic decentralized loyalty point management system using SMT structure where key is the user address and value is the point.
- [npm5](https://github.com/RetricSu/npm5): a simple type script that validate javascript package info and a CLI tool that use CKB as a code hosting platform for javascript libraries to replace npmjs.com.
- [ckb-js-pokemon](https://github.com/cryptape/ckb-js-pokemon): A blockchain-based Pokemon NFT collection platform built on CKB, allow users to purchase Pokemon NFTs using PokePoints (custom token system) and build their Pokemon collection with varying rarities and prices.
- [countdown-cell](https://github.com/tianlitao/ckb_count_down): A lightweight, fun, and extensible on-chain mini-game: each Cell has an expiration block, endBlock. Adding CKB to the Cell extends its expiration time proportionally and records the "last payer". When no further CKB is added, the last payer receives the entire reward.

## Contributing

We welcome contributions! To add a new script:

1. Fork the repository
2. Update README.md for your script explaining the concept
3. Submit a pull request

Please ensure your scripts are well-documented and include test cases where applicable.

## Resources

Use [offckb](https://github.com/ckb-devrel/offckb?tab=readme-ov-file#create-a-ckb-smart-contract-project) to create Your little Script project.

- [CKB Documentation](https://docs.nervos.org/)
- [ckb-js-vm GitHub](https://github.com/nervosnetwork/ckb-js-vm)
- [CKB Community](https://talk.nervos.org/)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Disclaimer

These scripts are for educational and demonstration purposes only. All scripts are unaudited.
