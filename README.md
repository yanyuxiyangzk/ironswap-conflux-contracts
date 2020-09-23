# ironswap-amm

## Migrator

- MigratorFactory

createpair and get Custodian RecevieAddress(cToken Type), from ethereum transfer then crosschain club mint cToken, transfer ERC777 to MigratorPair

- MigratorPair

receive crosschain fund; Add LIQUIDITY
user exchange LpToken through cIronLpToken;
upload User ShareAmount Then airdrop FC;

## IronSwap

- IronSwap Factory (=UniswapV2Factory)

same as Uniswap;

limit createPair;
limit tokenlist;

- IronSwap Pair (= UniswapV2Pair)

same as Uniswap;
