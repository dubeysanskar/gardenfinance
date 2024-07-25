# Deployment link(vercel)= https://gardenfinance-mu.vercel.app/

# Demo App

# A Journey Through Multichain Development
Embarking on this project was like diving into an ocean of knowledge and excitement. Each step unfolded new learnings and challenges, making the process as adventurous as it was educational.

# Discovering Merry
Installing and running Merry was our first big leap. With a simple bash command, Merry set up a multichain environment that felt like having a mini blockchain universe at our fingertips. Running merry go was exhilarating, knowing we were about to create something powerful.

# Setting Up the Swap Interface
Creating the swap interface was a blend of creativity and technicality. Watching the interface come to life, where users could seamlessly swap WBTC for BTC, was immensely satisfying. It wasn't just about coding; it was about crafting a tool that simplifies complex transactions.

# Managing Transactions
Tracking and displaying the latest transactions turned out to be a deep dive into the nuances of transaction management. It was fascinating to see how each transaction flowed through the system, teaching us the importance of efficient state management.

# Integrating Garden SDK
The integration of the Garden SDK was the heart of this project. Each function call, each parameter, and each successful swap felt like piecing together an intricate puzzle. It was a testament to how powerful and flexible the Garden SDK is, and how it can transform a simple idea into a functional dApp.

# State Management with Zustand
Zustand's state management capabilities were the cherry on top. It simplified our code and made the state management intuitive. Learning and implementing Zustand was a delightful experience, adding another tool to our developer toolkit.
<hr><hr><hr>

**By the end of this project, we didn't just create a dApp; we expanded our horizons, learned new technologies, and enjoyed the thrill of development. This wasn't just a project—it was an adventure, a learning journey that left us enriched and eager for more.**



<br><br><br><br><br><br><br>
# Given data (avoid reading that)...


This project demonstrates how to use the [Garden SDK](https://docs.garden.finance/developers/sdk/) to create a simple dApp for swapping from WBTC to BTC.

> [!NOTE]
> For better developer experience, we are conducting the swap on a local network, but you can do the same on Testnet or Mainnet by changing the parameters.

## Features

- **Merry** : Provides a comprehensive environment for multichain operations. 
- **Swap Interface**: Easily swap from WBTC to BTC.
- **Transaction Management**: Track and display the latest transactions.
- **Garden SDK Integration**: Uses Garden SDK to make the swap possible.
- **State Management**: We use [zustand](https://zustand-demo.pmnd.rs/) for state management.

## Environment Setup

To improve the developer experience, we will be using [Merry](https://docs.garden.finance/developers/merry/) to set up the multichain environment necessary for performing a swap. This setup includes all essential components such as the [Orderbook](https://docs.garden.finance/developers/fundamentals/orderbook/), [Filler](https://docs.garden.finance/developers/fundamentals/filler/), [Faucet](https://www.alchemy.com/faucets#faucets-switchback-right-light), and nodes for Bitcoin, Ethereum, and Arbitrum.

1. Install Merry

```bash
curl https://get.merry.dev | bash
```

2. Start Merry

```bash
# Start Merry with explorer
merry go
```

or

```bash
# Start Merry without explorer
merry go --headless
```

3. Fund your EVM address

```bash
 merry faucet --to <EVM Address>
```

## Project Setup

1. Clone the repository

```bash
git clone https://github.com/gardenfi/demo-app
cd demo-app
```

2. Install dependencies

```bash
bun install
```

3. Run the development server

```bash
bun run dev
```

The dApp should look something like this

![final_dapp](https://github.com/Sushants-Git/demo-app/assets/100516354/bf939a2f-3ac1-40f6-882c-c779ee4928ee)

