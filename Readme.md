#How to Setup this Repo:

## Clone Code Repo

## Make sure you’re on the localnet.
'''solana config set --url localhost'''

## Run the tests.
'''anchor test'''

## Build, deploy and start a local ledger.
'''anchor localnet'''

## Or
'''solana-test-validator'''

'''anchor build'''
'''anchor deploy'''

## Copy the new IDL to the frontend.
'''anchor run copy-idl'''

## Serve your frontend application locally (cd into app dir).
'''npm run serve'''

## Switch to the devnet cluster to deploy there.
'''solana config set --url devnet'''

## And update your Anchor.toml file.

## Airdrop yourself some money if necessary.
'''solana airdrop 5'''

## Build and deploy to devnet.
'''anchor build'''
'''anchor deploy'''

## Push your code to the main branch to auto-deploy on Netlify.
'''git push'''


# How to test deployed dev app:

## Download Phantom Chrome Extension.

## Follow steps the create a Solana wallet on Phantom.

## Switch Network to devnet from settings.

## Send me a request @gmail: goldipatel12@gmail.com for dev Solana Token (you need to provide me the public key of Phantom wallet)

## Visit: https://speak4u.netlify.app/ and test Speak4U Dapp.
