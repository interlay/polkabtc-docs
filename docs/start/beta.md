# Incentivized Beta Testnet

The interBTC Beta testnet is the final testing phase of the interBTC bridge prior to launch on Kusama and Polkadot.

It is of utmost importance to achieve a high participation rate to:
- Detect left-over bugs,
- Receive feedback from users regarding the UI/UX,
- Test the Vault and Staked Relayer client software,
- Test integrations with other applications/parachains,
- Test expected failures (e.g. exchange rate fluctuations, oracle crashes, …) and high operation under high system load.

## DOT Rewards

To achieve higher participation during Beta testnet, Interlay is organizing a number of events, competitions, and challenges to actively test critical components of the interBTC bridge.

Polkadot Council has approved **1300 DOT** treasury funding for the interBTC testnet campaign ([see approved Polkassembly proposal](https://polkadot.polkassembly.io/treasury/36)).

### Stay up-to-date with the Latest Updates

- Join our [Discord](https://discord.gg/KgCYK3MKSf)
- Follow [interBTC](https://twitter.com/interbtc) on Twitter
- Follow [Interlay](https://twitter.com/InterlayHQ) on Twitter

## Treasure Hunt (900 DOT)

Users must perform a list of actions to receive a small amount of DOT. To claim rewards, users must fill out the corresponding feedback form. Rewards are only paid out if the feedback form was filled out properly.

### End Users (award: 1 DOT per user for the first 500. 500 DOT in total)

1. Get testnet Bitcoin from a BTC faucet
1. Get testnet DOT from the interBTC faucet
1. Issue interBTC
1. Redeem interBTC
1. Fill in the user feedback form provided at [https://bridge.interlay.io/feedback](https://bridge.interlay.io/feedback)

### Vault (award: 4 DOT for the first 50, 200 DOT in total)

1. Download, build and run the Vault client [based on the guide](https://docs.interlay.io/#/vault/guide)
1. Register as a Vault and provide testnet DOT as collateral (automatically done on starting the client - verify on the [Vault dashboard](https://bridge.interlay.io/dashboard/vaults))
1. Run the Vault
1. Serve at least 5 issue and 5 redeem requests
1. Maintain an SLA of 99% or higher for at least 24h
1. Fill in the Vault feedback form provided at [https://bridge.interlay.io/feedback](https://bridge.interlay.io/feedback)

### Staked Relayer (award: 4 DOT for the first 50, 200 DOT in total)

1. Download, build and run the Staked Relayer client [based on the guide](https://docs.interlay.io/#/relayer/guide)
1. Run the Staked Relayer
1. Submit at least 1 Bitcoin testnet block
1. Maintain an SLA of 99% or higher for at least 24h
1. Fill in the Staked Relayer feedback form provided at [https://bridge.interlay.io/feedback](https://bridge.interlay.io/feedback)

## King of the Hill: Vaults and Relayers (200 DOT)

!> Important: You will need to submit your Polkadot address (starting with "1..") to participate in the king of the hill contest. Otherwise, we cannot match your address on the interBTC bridge with your Polkadot address. If you already have submitted your DOT address via the form (https://forms.gle/V6LsUb3J9qR6oJCN8), you don't need to do it again.

We compute a lifetime SLA score for Vaults and Staked Relayers (each desirable action adds to the score, a failure to Redeem reduces the score significantly).
In the King of the Hill challenge, the top 10 Vaults and Relayers are rewarded with DOT at the end of each week for a period of 2 weeks (2 rounds). Scores are reset each week allowing new Vaults and Staked Relayers to join and have the chance to earn DOT rewards for participating.

### Vaults (award: 150 DOT for the top 5 according to their SLA score starting on June 2, 2021)

1. Download, build and run the Vault client [based on the guide](https://docs.interlay.io/#/vault/guide)
1. Register as a Vault and provide testnet DOT as collateral (automatically done on starting the client - verify on the [Vault dashboard](https://bridge.interlay.io/dashboard/vaults))
1. Run the Vault and automatically earn SLA points
1. Fill in the form to receive DOT: [https://forms.gle/V6LsUb3J9qR6oJCN8](https://forms.gle/V6LsUb3J9qR6oJCN8)
1. Week 1-2: The top 5 Vaults will be selected and a total of 75 DOT is distributed to them each week

### Staked Relayer (award: 50 DOT for the top 5 according to their SLA score starting on June 2, 2021)

1. Download, build and run the Staked Relayer client [based on the guide](https://docs.interlay.io/#/relayer/guide)
1. Register as a Staked Relayer and provide testnet DOT as collateral (automatically done on starting the client - verify on the [Relayer dashboard](https://bridge.interlay.io/dashboard/parachain))
1. Run the Staked Relayer and automatically earn SLA points
1. Fill in the form to receive DOT: [https://forms.gle/V6LsUb3J9qR6oJCN8](https://forms.gle/V6LsUb3J9qR6oJCN8)
1. Week 1-2: The top 5 Staked Relayers will be selected and a total of 25 DOT is distributed to them each week

## Lottery (200 DOT)

!> Important: You will need to submit your Polkadot address (starting with "1..") to participate in the lottery. Otherwise we cannot match your address on the interBTC bridge with your Polkadot address. If you already have submitted your DOT address via the form (https://forms.gle/V6LsUb3J9qR6oJCN8), you don't need to do it again.

To provide more incentive for users to create numerous transactions and stress-test the system, we are running a lottery.
The lottery will run for four weeks and each week a payout of 50 DOT is made.

### Users

1. Create issue and redeem requests via the [interBTC app](https://bridge.interlay.io/app) or feel free to automate this process using the [interbtc-js library](https://github.com/interlay/interbtc-js) (size doesn't matter - create as many as you like to increase your chance of winning)
1. Make sure that the requests are completed (issue and redeem requests executed). Only executed requests qualify for the lottery.
1. Fill in the form to receive DOT: [https://forms.gle/V6LsUb3J9qR6oJCN8](https://forms.gle/V6LsUb3J9qR6oJCN8)
1. Week 1-4: Interlay will select one issue and one redeem request at random.
1. For each randomly selected request, a reward of 20 DOT is made.

### Vaults

1. Create replace requests via the [Vault dashboard](https://bridge.interlay.io/vault) ("Replace my Vault" button)
1. Make sure that the requests are at least partially completed (one other vault has accepted your request). Only executed requests qualify for the lottery.
1. Fill in the form to receive DOT: [https://forms.gle/V6LsUb3J9qR6oJCN8](https://forms.gle/V6LsUb3J9qR6oJCN8)
1. Week 1-4: Interlay will select one replace request at random.
1. For each randomly selected request, a reward of 10 DOT is made.
