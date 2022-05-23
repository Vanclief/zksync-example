# ZkSync Developer Quickstart

This is the code from the [ZkSync Developer Quickstart](https://v2-docs.zksync.io/dev/guide/quickstart.html) Hello World tutorial. 

Disclaimer: I am not affiliated in any way with the zkSync team.


## Instructions

1. **Clone the repository**

```bash
git clone https://github.com/Vanclief/zksync-example.git 
```

2. **Install the dependencies**

`yarn install`

3. **Get tokens from the zkSync faucet**

Go to the [zkSync portal](https://portal.zksync.io/), login with your Metamask wallet and click on Faucet from the left menu bar.



3. **Add your private key**

Add your private key to the `deploy/deply.ts` file:

`const wallet = new Wallet("0x..."); // Your private key goes here`


4. **Compile the contract**

`yarn hardhat compile`


5. Deploy the contract

`yarn hardhat deploy-zksync`

