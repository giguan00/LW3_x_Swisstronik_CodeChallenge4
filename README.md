# Swisstronik x Learn Web 3 Challenge 4 

In this project, there are sample contracts, tests, and scripts that deploy contracts, as well as the Swisstronik blockchain network. This case demonstrates the basic usage of Hardhat.

## Task

1. Deploy an ERC20 token
2. Mint tokens
3. Transfer at least 1 of your ERC20 tokens to 0x16af037878a6cAce2Ea29d39A3757aC2F6F7aac1

## Token Details

```
Name    : GIGUAN WELL PLAYED
Symbol  : GGWP
```

## Smart Contract

```
0xAe279ee98ca306E30EF1F3AF2F39fb849A584f6c
```


### Network: Swisstronik


#### `Function Deploy`

```shell
npx hardhat run scripts/deploy.js --network swisstronik
```
Response :


#### `Function Mint`

```shell
npx hardhat run scripts/mint.js --network swisstronik
```

```shell
function mint100tokens() public {
 _mint(msg.sender,100*10**18);
}
```

#### `Function Transfer`

```shell
npx hardhat run scripts/transfer.js --network swisstronik
```
Hash
```
0x74a43d2ae455b52440413b2a777e83fee0872ea541a19c01b96e34fae6648ff5
```

### `Bonus Scripts`

#### `Confirm you was succesfully sent token and completed task with balanceOf script`

This scripts to validate your token has successfully transfer to 0x16af037878a6cAce2Ea29d39A3757aC2F6F7aac1

```shell
npx hardhat run scripts/balanceOf.js --network swisstronik
```
```
Response:
Decoded response: 1n
```

## Conclusion

Tx hash Deploy
```
https://explorer-evm.testnet.swisstronik.com/tx/0x8fe07a8bb107162c33406f972d320895ffbbccdc59f6238cb236b4c9debedb7c
```

Tx hash Mint
```
https://explorer-evm.testnet.swisstronik.com/tx/0xf8c32ce5282d7ba8611a8840153ad6a79e97dfd59c195f18e5a222193bb36d20
```

Tx hash Transfer
```
https://explorer-evm.testnet.swisstronik.com/tx/0x74a43d2ae455b52440413b2a777e83fee0872ea541a19c01b96e34fae6648ff5
```

