import { Callout } from "components";

# Stake mGNO token

To stake mGNO, you'll need to:
1. Purchase GNO on Ethereum.
2. Bridge GNO to Gnosis.
3. Convert the bridged GNO to mGNO.
4. Connect your wallet at Ankr Staking.
5. Stake mGNO at Ankr.

## Before you start

Ensure the following:
* You are using a Chrome Browser.
* You have a [MetaMask wallet extension](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn) installed and set up in Chrome.

## Get GNO
Visit one of the [recommended DEXs](https://docs.gnosischain.com/ecosystems/defi#dex-aggregators) and swap your assets for the desired amount of GNO tokens.

<Callout type="info">
You'll need a small amount of xDai for gas fees while depositing GNO and staking mGNO.
</Callout>

## Bridge GNO to Gnosis Chain
Your obtained GNO is likely to be the Ethereum Mainnet GNO version.
To use it on Gnosis, you'll need to bridge it to Gnosis Chain.

* Use the [OmniBridge](https://omni.gnosischain.com/bridge) to move GNO from Ethereum to Gnosis Chain.
* Add Gnosis to your wallet, visiting [Ankr Gnosis RPC page](https://www.ankr.com/rpc/gnosis/) and clicking **Add network**. Alternatively, use [these manual instructions](https://docs.gnosischain.com/tools/wallets/metamask) from Gnosis.

## Convert the bridged GNO to mGNO
<Callout type="info">
Make sure you have some xDai to pay the gas fee for your depositing transaction.<br/>
Remember that mGNO will remain locked and illiquid until ~Q4 2023 max.
This is due to Gnosis plans to enable withdrawals in the Shanghai upgrade. Shanghai is planned in 6–12 months from The Merge that is expected in ~Q3/Q4 2022.
</Callout>
To convert your bridged GNO to mGNO: 
1. Visit the GNO–mGNO converter at https://mgno.validategnosis.com/.
2. Connect your wallet.
   <img src="/docs/staking/delegated-staking/mgno/gno-mgno-converter-connect-wallet.png" alt="Connect wallet" class="responsive-pic" width="400" />
3. Choose the amount you would like to convert and click **Convert**. You can convert any amount, be sure to start with a leading 0 to convert less than 1 GNO. For example, 0.1 GNO will be converted to 3.2 mGNO.
   <img src="/docs/staking/delegated-staking/mgno/gno-mgno-converter-click-convert.png" alt="Click Convert" class="responsive-pic" width="400" />
4. Sign the transactions in your wallet. This will require a small amount of xDai to complete.
5. The transaction should be initiated and completed within a few seconds. Once completed you can click the link to see the tx details and add mGNO to your MetaMask wallet.
   <img src="/docs/staking/delegated-staking/mgno/gno-mgno-converter-add-mgno-to-metamask.png" alt="Check tx details and add mGNO to Metamask" class="responsive-pic" width="400" />

When done, you're ready to stake your mGNO on Ankr Staking. 

## Connect your wallet
1. Visit [Ankr Staking Dashboard](https://www.ankr.com/staking/dashboard/).
   <img src="/docs/staking/connect-wallet/ankr-staking.jpg" alt="Connect wallet button" class="responsive-pic" width="600" />
2. Click **Connect wallet** in the top-right corner of the page.
   <img src="/docs/staking/connect-wallet/connect-wallet-button.jpg" alt="Connect wallet button" class="responsive-pic" width="140" />
3. Choose **MetaMask**.
   <img src="/docs/staking/connect-wallet/choose-wallet-to-connect.jpg" alt="Connect wallet button" class="responsive-pic" width="500" />
4. If you have multiple accounts in MetaMask, choose an account to connect and click **Next**.
   <img src="/docs/staking/connect-wallet/choose-account-to-connect.jpg" alt="Choose an account" class="responsive-pic" width="300" />
5. Click **Connect** and wait for a couple of moments till the connecting process is finished.
   <img src="/docs/staking/connect-wallet/connect-account.jpg" alt="Connect the account" class="responsive-pic" width="300" />
6. Successful connection to **Ankr Staking** is indicated at top right corner by the address of wallet you connected.
   <img src="/docs/staking/connect-wallet/wallet-connected.jpg" alt="Wallet connected" class="responsive-pic" width="220" />
7. If asked by Ankr Staking to switch networks, select a network of your choice.
   <img src="/docs/staking/connect-wallet/select-supported-network.jpg" alt="Select a supported network" class="responsive-pic" width="500" />
8. Click **Switch network** to confirm switching.
   <img src="/docs/staking/connect-wallet/confirm-switching-networks-gnosis.jpg" alt="Confirm switching networks" class="responsive-pic" width="300" />

## Stake mGNO

<Callout type="info">
Your stake does not immediately gets staked on Gnosis.
Gnosis accepts stakes with minumum 1 GNO (32 mGNO).
To bypass this and accept your stake if it's lower than 1 GNO, we created a micropool that accumulates user stakes.
Once it has 1 GNO, we stake it with Gnosis.<br/>
Make sure you have some xDai to pay the gas fee for your staking transaction.
</Callout>

1. Visit [Ankr Staking](https://www.ankr.com/staking/stake).
2. In the **Delegated staking** section, click **Stake** under **mGNO**.
   <img src="/docs/staking/delegated-staking/mgno/mgno-staking-box.jpg" alt="Locate the mGNO box" class="responsive-pic" width="500" /> 
3. Choose a Node Provider (currently only Ankr; more providers in future releases).
   <img src="/docs/staking/delegated-staking/mgno/choose-node-provider.jpg" alt="Choose a Node Provider" class="responsive-pic" width="500" />
5. Enter the desired amount to unstake and click **Approve** to allow Ankr Staking smart contracts to unstake for you.
   <img src="/docs/staking/delegated-staking/mgno/enter-amount-click-approve.jpg" alt="Enter an amount and click Approve" class="responsive-pic" width="500" />
6. Confirm your approval in MetaMask.
   <img src="/docs/staking/delegated-staking/mgno/confirm-approval.jpg" alt="Confirm your approval" class="responsive-pic" width="300" />
7. Click **Stake** to send your delegated stake to the chosen Node Provider..
   <img src="/docs/staking/delegated-staking/mgno/click-stake.jpg" alt="Click Stake" class="responsive-pic" width="500" />
8. Confirm the staking transaction in MetaMask.
   <img src="/docs/staking/delegated-staking/mgno/confirm-staking-transaction.jpg" alt="Confirm staking transaction" class="responsive-pic" width="300" />
9. Click **Go to dashboard** to see the added token. You may need to wait a little for the transaction to finalize and **Dashboard** to automatically update.
   <img src="/docs/staking/liquid-staking/ftm/click-go-to-dashboard.jpg" alt="Click Go to dashboard" class="responsive-pic" width="550" />