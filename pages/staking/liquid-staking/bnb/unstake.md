import { Callout } from "components";

# Unstake BNB

## Unstake options
You have two options when unstaking:
1. Standard unstake — up to 7–10 days before you receive your funds, but no commission or limits.
2. Flash unstake — instant release of your funds, 0.5% commission, and unstake limits dictated by the current capacity of the flash-unstake pool.

### Standard unstake
Standard unstake can take up to 7–10 days until your funds are released to your wallet.

This is because of the BNB Chain restriction, where the processing time of an unstaking transaction is 7 days.

1. Because of this restriction, Ankr has to accumulate all unstaking transactions from users in a pool.
2. Once every 24 hours, Ankr checks any of the 5 available validators are free, i.e. are not processing a pending unstaking transaction.
3. When such validator is found, Ankr sends it an unstaking transaction with the amount equal to the aggregate of all the user transaction since the last Ankr unstaking transaction.
4. This Ankr transaction takes 7 days to be processes, which is the BNB Chain unbond time period.
5. After the unbond time period ends, Ankr receives the unstaked funds and redistributes them to the users.

### Flash unstake
Flash unstake uses a pool to swap your Liquid Staking tokens for your original assets, which means instant release of your funds.

While it offers instant release of your funds, it poses a few limitations:
1. You have to pay a flash-unstake fee, which is 0.5% of the amount you're unstaking.
2. Your unstake is limited by the current capacity of the flash-unstake pool. If you exceed it, the interface switches to the standard unstake with its regular release time.

## Unstake BNB 
<Callout type="info">
Ensure you have a small amount of BNB to pay the Binance gas fee for your unstaking transaction.
</Callout>

1. Open [Ankr Staking Dashboard](https://www.ankr.com/staking/dashboard/). 
2. Locate the ankrBNB box and click the **-** icon to unstake.
   <img src="/docs/staking/liquid-staking/bnb/click-minus-icon.jpg" alt="Click the minus icon" class="responsive-pic" width="800" />
3. Enter the desired amount to unstake and click **Approve** to allow Ankr Staking smart contracts to unstake for you.
   <img src="/docs/staking/liquid-staking/bnb/enter-amount-click-approve.jpg" alt="Enter an amount and click Approve" class="responsive-pic" width="400" />
4. Confirm your approval in MetaMask.
   <img src="/docs/staking/liquid-staking/bnb/confirm-approval.jpg" alt="Confirm your approval" class="responsive-pic" width="300" />
5. Click **Unstake** to unstake the desired amount.
   <img src="/docs/staking/liquid-staking/bnb/click-unstake.jpg" alt="Click Unstake" class="responsive-pic" width="400" />
6. Confirm the unstaking transaction in MetaMask.
   <img src="/docs/staking/liquid-staking/bnb/confirm-unstaking-transaction.jpg" alt="Confirm transaction in MetaMask" class="responsive-pic" width="300" />
7. On the next **Unstake in progress page**, click **Go to dashboard**.
   <img src="/docs/staking/liquid-staking/bnb/unstake-in-progress-go-to-dashboard.jpg" alt="Click Go to dashboard" class="responsive-pic" width="550" />

<Callout type="success">
Once transaction is confirmed, Ankr Staking Dashboard updates to show **Unstaking in progress** at the token box.<br/>
</Callout>

