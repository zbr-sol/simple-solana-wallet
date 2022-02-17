# Wallet Tutorial
This is an extremely simple implementation of a wallet for the [Solana](https://solana.com/) protocol. Figment (more details below) provided a simple [Next.js](https://nextjs.org/) application that I completed by leveraging Solana's [JavaScript SDK](https://solana-labs.github.io/solana-web3.js/index.html).

If you follow my commit history, you can see that we built this wallet in a few discrete steps:
1. Create the wallet by generating a mnemonic device and converting it to seed bytes. We can then create a new "account" using this seed.  
2. Be able to fetch the SOL balance from this wallet address
3. Request an airdrop of 1 SOL to this address from a devnet "faucet"
4. Be able to send/transfer funds to any other wallet address
5. Log out and "recover" an account by importing the seed/recovery phrase generated in step 1

![](./public/wallet-tutorial-screenshot.png)

## 🤔 What is the `wallet-dapp`?

Crypto wallets are one of the foundations of Web 3. They are the gateway application into crypto ecosystems by enabling users to interact with blockchain protocols and manage digital assets.

## 🔩 Designed by Figment Learn
*NOTE - all of the front-end code was provided from a tutorial built by the Figment team. Copying their original github message below:
*
Our goal at [Figment Learn](https://learn.figment.io/) is to build the best resources for developers learning about and building in Web 3. We really hope you enjoy the tutorial and thanks for checking it out. **WAGMI!**

Learn more about [Figment](https://figment.io/) and [Figment Learn](https://learn.figment.io/).

[Join us on Discord](https://discord.com/invite/fszyM7K) if you have any feedback or questions!

-- The Figment Learn Team
