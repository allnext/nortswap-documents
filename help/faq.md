# General FAQ

![](../.gitbook/assets/docs-masthead-17-.png)

This FAQ page answers some of the more commonly asked questions from the Nortswap community.

## Is Nortswap safe? Has Nortswap been Audited?

See for yourself:

- Check out these Nortswap security audits:
  - [Certik’s security audit of Nortswap](https://www.certik.org/projects/nortswap) and [Certik's Shield insurance](https://shield.certik.foundation)
  - [Slowmist's security audit of Nortswap](https://github.com/slowmist/Knowledge-Base/blob/master/open-report/Smart%20Contract%20Security%20Audit%20Report%20%20-%20Nortswap.pdf)
  - [Slowmist's Auto-NT Pool security audit](https://github.com/slowmist/Knowledge-Base/blob/master/open-report/Smart%20Contract%20Security%20Audit%20Report%20-%20CakeVault.pdf)
  - [Peckshield's Lottery V2 Audit](https://github.com/peckshield/publications/blob/master/audit_reports/PeckShield-Audit-Report-NortswapLottery-v1.0.pdf)
  - [Slowmist's Lottery V2 Audit](https://github.com/slowmist/Knowledge-Base/blob/master/open-report/Smart%20Contract%20Security%20Audit%20Report%20-%20Nortswap%20Lottery.pdf)
- Transparent:
  - We’re built on open-source software: our site and all our Smart Contracts are publicly visible for maximum transparency.
  - Our contracts are verified on BscScan so you know that what you see is what you get: [1](https://bscscan.com/address/0x10ED43C718714eb63d5aA57B78B54704E256024E) [2](https://bscscan.com/address/0x73feaa1ee314f8c655e354234017be2193c9e24e#code) [3](https://bscscan.com/address/0xbcfccbde45ce874adcb698cc183debcf17952812) [4](https://bscscan.com/address/0x1b96b92314c44b159149f7e0303511fb2fc4774f#code) [5](https://bscscan.com/address/0x92E8CeB7eAeD69fB6E4d9dA43F605D2610214E68)
- Security best practices:
  - The chefs use multisig for all contracts.
  - Our contracts’ time-lock gives you peace of mind.

## How can I stake NT?

You can stake your NT in Nortswap Syrup Pools. Visit the [Syrup Pools page](https://nortswap.finance/pools).

Read our [How to Stake in Syrup Pools guide](https://docs.nortswap.finance/products/syrup-pool/syrup-pool-guide) if you'd like a hand getting started with staking.

## What is the difference between staking and farming?

Staking in Syrup Pools and farming with Yield Farming are both ways to earn more NT by supporting Nortswap.

Staking only needs some NT to be added to a Syrup Pool to earn NT or other tokens.\
[Learn more about Syrup Pool staking.](https://docs.nortswap.finance/products/syrup-pool)

Farming is more complicated and needs LP Tokens to earn NT.\
[Learn more about Yield Farming.](https://docs.nortswap.finance/products/yield-farming)

## How do I farm?

We have a [Yield Farming guide](https://docs.nortswap.finance/products/yield-farming/how-to-use-farms) if you're interested in learning how to farm.

## Where can I view the Nortswap roadmap?

You can [view our to-do list here, but don't call it a roadmap](https://docs.nortswap.finance/roadmap).

## How do I connect my wallet to Binance Smart Chain and Nortswap?

We have a [Connect Your Wallet to Nortswap guide](https://docs.nortswap.finance/get-started/connection-guide) covering this in detail.

## What's the best wallet for Nortswap?

It depends on your needs. We have an [in-depth guide to selecting and creating a wallet](https://docs.nortswap.finance/get-started/wallet-guide) that's right for you.

## Why is my transaction failing?

You can check the status of a transaction on [https://bscscan.com/](https://bscscan.com).

Our [Troubleshooting Errors guide](https://docs.nortswap.finance/help/troubleshooting) may have a solution for your problem if you're having issues.

You can also see our [Fixing Stuck Pending Transactions guide](https://docs.nortswap.finance/help/unsticking-a-transaction-stuck-as-pending-with-metamask) if you have a stuck transaction.

## When will you open more pools?

New Pools are added to Nortswap frequently. There will always be an announcement before the launch of new pools.

Join the [announcements Telegram group](https://t.me/NortswapAnn) to learn about new Pools as early as possible.

## Did Farm APR calculation change?

Previously, rewards earned by LP Token-holders generated from trading fees were not included in Farm APR calculations. APR calculations now include these rewards, and better reflect the expected APR for Farm pairs.

## How do I get airdrops?

Whenever there is an official airdrop on Nortswap it will be announced along with the requirements.

Please remember anyone can airdrop tokens to Nortswap users since every transaction is public on BscScan. Be sure to do your own research when it comes to non-official airdrops. To protect your funds, we recommend you don't use a smart contract you don't understand from a source you don't trust.

## How can I report a bug?

Learn about our [bug bounty and potential bounty payouts](https://docs.nortswap.finance/code/bug-bounty).

## Where can I view smart contracts?

Learn how to find smart contracts on our [Finding Contracts page](https://docs.nortswap.finance/code/smart-contracts/finding-contracts).

## Why does it say I have no BNB balance?

If you've already [transferred BNB into your Binance Smart Chain-enabled wallet](https://docs.nortswap.finance/get-started/bep20-guide) but still have this error, you're most likely not [connected to Binance Smart Chain](https://docs.nortswap.finance/get-started/connection-guide) within your wallet. Check your wallet's selected network and make sure you have Binance Smart Chain (BSC) selected.

## How do I vote?

To learn more about voting, you can [read our section on Voting](https://docs.nortswap.finance/products/voting), including voting guides.

## What is the max supply of NT?

$NT does not have a maximum supply. The circulating supply is managed through built-in burning and regular burning events.\
\
Read this to [learn more about Nortswap's tokenomics](https://docs.nortswap.finance/tokenomics/cake).

## What are the treasury funds used for?

The treasury funds are used to cover the expenses involved in running Nortswap. These expenses include salaries, audits, prizes, hosting, upkeep, bounties, etc.

## Where can I check the Analytics?

You can check the analytics of Nortswap by click on the "Analytics" tab on the top menu or by clicking the link below.

Analytics: [https://nortswap.info/](https://nortswap.info)

## Is Nortswap protected from flashloan attacks?

Nortswap's vault has anti-flashloan protection. Nortswap’s NT token isn’t vulnerable to flash loan attacks. Unlike vulnerable tokens, NT token minting is predefined, and can’t be adjusted in a single transaction. Ownership cannot be transferred outside of MasterChef contract.

Nortswap’s other smart contracts, like IFO and AutoPool, are protected as well; they prevent other contracts from interacting with them, reducing the scope of vector attacks.

## Can I join the Nortswap team?

Check the [Become a Chef](https://docs.nortswap.finance/hiring/become-a-chef) area for information on open positions we're looking to fill.

We advertise new positions we're looking to fill on our [official social media channels](https://docs.nortswap.finance/contact-us/telegram), so be sure to follow us to get the latest hiring information.

## What is SYRUP?

SYRUP was a part of the staking process earlier in Nortswap's life. SYRUP was discontinued when a security issue was discovered and is no longer a part of Nortswap.

## I can't find an answer for my question. Where do I find an answer?

If you can't find what you're looking for in Nortswap's documentation, ask your question on [Nortswap's official social media platforms](https://docs.nortswap.finance/contact-us/telegram) and someone will do their best to help you out.
