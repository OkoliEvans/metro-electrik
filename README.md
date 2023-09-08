## Metro eletrik

**Metro eletrik is an on-chain electricitiy subscription system where energy users can buy uints using cryptocurrencies.**

How to:

-   **Create Disco**: Electricity distribution companies can create business profile on the platform, passing in required parameters 
-   **BuyWithUSDC**: Subscribers can either buy units with USDC or Ether. To buy with USDC, select "buy with USDC", then pass in meterNo and the unit amount to recharge. 
-   **BuyWithEther**: To buy units with Ether, select "buy with Ether", pass in your meter number and the amount of Ether you want to subscribe. First time subscribers are rewarded with some Metro tokens.
-   **setUnitPrice**: 

## Documentation

https://book.getfoundry.sh/

## Usage

### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```

### Format

```shell
$ forge fmt
```

### Gas Snapshots

```shell
$ forge snapshot
```

### Anvil

```shell
$ anvil
```

### Deploy

```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```

### Cast

```shell
$ cast <subcommand>
```

### Help

```shell
$ forge --help
$ anvil --help
$ cast --help
```
