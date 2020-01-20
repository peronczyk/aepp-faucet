# aepp-faucet

Send Online Top-up. Instant Wallet Recharge

Recharge your wallet on the aeternity testnet https://sdk-testnet.aepps.com

## Configuration

Configuring Faucet application via enviornment variable:

- `TOPUP_AMOUNT` The amount of tokens that the faucet application will place into your account. (Default value 5AE)
- `FAUCET_ACCOUNT_PRIV_KEY` The account that faucet aepp will top off the account.
- `EPOCH_URL` URL of the node that the faucet aepp is using. (Default value 'https://sdk-testnet.aepps.com')
- `EPOCH_URL_DEBUG` URL of the node that the faucet aepp is using (debug endpoints). (Default value 'https://sdk-testnet.aepps.com')
- `TX_TTL` How many key blocks will live before it is mined (Default value 100)
- `EXPLORER_URL` Url of the explorer app (Default value 'https://testnet.explorer.aepps.com')
- `TX_PAYLOAD` Value to use to fill the payload for the transactions (Default value `Faucet Tx`)
- `NETWORK_ID` The network id (Default value `ae_uat`)

### Telegram integration

- `TELEGRAM_API_TOKEN` the token of the telegram bot. Disables the integration if not set. (Default value "not set")
- `TELEGRAM_CHAT_ID` the chat id to send notifications to

## Front-End Development

1. Run `npm i` from the root of the project
2. Run `npm run dev` to start webpack


### Dev notes:
- All the Front-End resources are in `/src/`
- Run `npm run prod` to compile assets for production
- Compiled assets (`prod` or `dev`) will be created in `/assets/`
