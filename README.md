## Metro eletrik

**Metro eletrik is an on-chain electricitiy subscription system where energy users can buy uints using cryptocurrencies.**

How to:

-   **Create Disco**: Electricity distribution companies can create business profile on the platform, passing in required parameters 
-   **BuyWithUSDC**: Subscribers can either buy units with USDC or Ether. To buy with USDC, select "buy with USDC", then pass in meterNo and the unit amount to recharge. 
-   **BuyWithEther**: To buy units with Ether, select "buy with Ether", pass in your meter number and the amount of Ether you want to subscribe. First time subscribers are rewarded with some Metro tokens.
-   **setUnitPrice**: Registered electricity distribution companies can update their unit prices using the "setUnitPrice" function. Only the account assigned as the company admin can perform this.

- **withdrawEther**: Registered companies can withdraw their Ether easily from the platform by using this function. This can only be performed bby the assigned admin for each company.

- **withdrawUSDC**: Almost the same with **withdrawEther**, but the token to withdraw here is USDC.

## Developers

### Start
```shell
$ git clone https://github.com/OkoliEvans/metro-electrik
```

### Installation

```shell
$ cd backend
$ forge install
```

### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```

### Deploy


```shell
$ forge --help
```
