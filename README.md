
## Devnet
### Start the devnet

```shell
cd docker
docker compose up -d
```

### Deploy the contracts to devent

```
npm install
npx @alephium/cli compile
npx @alephium/cli deploy -n devnet
```

### Start the ui

```
npm run dev
```

## Testnet

Start the UI and launch the deployed demo dapp with the following command:

```
NEXT_PUBLIC_NETWORK=testnet npm run dev
```
