# Little CKB Script

A curated collection of small on-chain script demos for the CKB (Common Knowledge Base) blockchain. This project aims to showcase and educate developers on writing smart contracts and scripts for CKB, with a focus on simplicity and accessibility.

Most scripts are written in JavaScript using [ckb-js-vm](https://github.com/nervosnetwork/ckb-js-vm), which lowers the barrier to entry by allowing developers to write CKB scripts in a familiar language without needing to learn Rust or other low-level languages.

## List

### Lock

- [hash-lock](https://github.com/nervosnetwork/docs.nervos.org/tree/develop/examples/dApp/simple-lock): a simple hash-lock script that can be unlocked by providing a preimage
- [simple-htlc](https://github.com/RetricSu/simple-htlc): a simple htlc script that can be unlocked by providing a preimage or a timeout refund.
- [SpilmanPayment](https://github.com/HappySonnyDev/SpilmanPayment/tree/main): a Spilman payment channel implemented on CKB, used in AI large-model streaming payment scenarios.

### Type

- [merkle-point](https://github.com/RetricSu/merkle-point): a simple type script that implement a basic decentralized loyalty point management system using SMT structure where key is the user address and value is the point.
- [npm5](https://github.com/RetricSu/npm5): a simple type script that validate javascript package info and a CLI tool that use CKB as a code hosting platform for javascript libraries to replace npmjs.com.
- [ckb-js-pokemon](https://github.com/cryptape/ckb-js-pokemon): A blockchain-based Pokemon NFT collection platform built on CKB, allow users to purchase Pokemon NFTs using PokePoints (custom token system) and build their Pokemon collection with varying rarities and prices.

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
