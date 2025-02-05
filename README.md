# tezos-ethereum-bridge
A simple "liquidity pool" based bridge between Tezos and Ethereum

1
`cd ethereum`
`pnpm install -g truffle ethers`
`truffle init`

2
`cd tezos`
`pnpm install @openzeppelin/contracts dotenv`
`pnpm install -g @completium/completium-cli`
`completium-init`
`pnpm install @taquito/taquito @taquito/signer`

3
`cd relay`
`pnpm init -y`
`pnpm install ethers @taquito/taquito axios dotenv`