## Dex subgraph

This is a fork of the uniswap v2 subgraph

## Connect to a the Node

```
npx graph auth https://api.thegraph.com/deploy/ <AUTH_TOKEN>
```

## Deploy to staging (goerli)

- un-comment staging variables in `src/mappings/environment.ts`
- `npm run codegen-staging`
- `npm run build-staging`
- `npm run deploy-staging`

## Deploy to prod (mainnet)

- un-comment prod variables in `src/mappings/environment.ts`
- `npm run codegen-prod`
- `npm run build-prod`
- `npm run deploy-prod`
