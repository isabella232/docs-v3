# Avalanche

## Core & Periphery contracts

{% hint style="warning" %}
_Pool_, _PoolConfigurator_, _Incentives_ and _Treasury_ addresses mentioned below are of Upgradeable Proxy contract. While interacting please use _abi_ of implementation contracts or generate abi from the github source code linked.&#x20;
{% endhint %}

| Contract                      | Github                                                                                                                        | Address                                    |
| ----------------------------- | ----------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------ |
| ACLManager                    | [Github](https://github.com/aave/aave-v3-core/blob/master/contracts/protocol/configuration/ACLManager.sol)                    | 0xa72636CbcAa8F5FF95B2cc47F3CDEe83F3294a0B |
| Pool                          | [Github](https://github.com/aave/aave-v3-core/blob/master/contracts/protocol/pool/Pool.sol)                                   | 0x794a61358D6845594F94dc1DB02A252b5b4814aD |
| PoolConfigurator              | [Github](https://github.com/aave/aave-v3-core/blob/master/contracts/protocol/pool/PoolConfigurator.sol)                       | 0x8145eddDf43f50276641b55bd3AD95944510021E |
| Incentives                    | [Github](https://github.com/aave/aave-v3-periphery/blob/master/contracts/rewards/RewardsController.sol)                       | 0x929EC64c34a17401F460460D4B9390518E5B473e |
| PoolAddressesProvider         | [Github](https://github.com/aave/aave-v3-core/blob/master/contracts/protocol/configuration/PoolAddressesProvider.sol)         | 0xa97684ead0e402dC232d5A977953DF7ECBaB3CDb |
| PoolAddressesProviderRegistry | [Github](https://github.com/aave/aave-v3-core/blob/master/contracts/protocol/configuration/PoolAddressesProviderRegistry.sol) | 0x770ef9f4fe897e59daCc474EF11238303F9552b6 |
| PoolDataProvider              | [Github](https://github.com/aave/aave-v3-core/blob/master/contracts/misc/AaveProtocolDataProvider.sol)                        | 0x69FA688f1Dc47d4B5d8029D5a35FB7a548310654 |
| UiIncentiveDataProviderV3     | [Github](https://github.com/aave/aave-v3-periphery/blob/master/contracts/misc/UiIncentiveDataProviderV3.sol)                  | 0x270f51cf3F681010B46f5c4Ee2aD5120Db33026F |
| UiPoolDataProviderV3          | [Github](https://github.com/aave/aave-v3-periphery/blob/master/contracts/misc/UiPoolDataProviderV3.sol)                       | 0xdBbFaFC45983B4659E368a3025b81f69Ab6E5093 |
| WETHGateway                   | [Github](https://github.com/aave/aave-v3-periphery/blob/master/contracts/misc/WETHGateway.sol)                                | 0xa938d8536aEed1Bd48f548380394Ab30Aa11B00E |
| WalletBalanceProvider         | [Github](https://github.com/aave/aave-v3-periphery/blob/master/contracts/misc/WalletBalanceProvider.sol)                      | 0xBc790382B3686abffE4be14A030A96aC6154023a |
| AaveOracle                    | [Github](https://github.com/aave/aave-v3-core/blob/master/contracts/misc/AaveOracle.sol)                                      | 0xEBd36016B3eD09D4693Ed4251c67Bd858c3c7C9C |
| Treasury                      | [Github](https://github.com/aave/aave-v3-periphery/blob/master/contracts/treasury/Collector.sol)                              | 0x5ba7fd868c40c16f7aDfAe6CF87121E13FC2F7a0 |
| TreasuryController            | [Github](https://github.com/aave/aave-v3-periphery/blob/master/contracts/treasury/CollectorController.sol)                    | 0xaCbE7d574EF8dC39435577eb638167Aca74F79f0 |
| ParaSwapLiquiditySwapAdapter  | [Github](https://github.com/aave/aave-v3-periphery/blob/master/contracts/adapters/paraswap/ParaSwapLiquiditySwapAdapter.sol)  | 0xAe02ECA9445ec43B53118DD41658DB17eaB55987 |
| ParaSwapRepayAdapter          | [Github](https://github.com/aave/aave-v3-periphery/blob/master/contracts/adapters/paraswap/ParaSwapRepayAdapter.sol)          | 0xA911965AbBE61460cB91f8259a8dF8509D877EBc |
| FallbackOracle                | [Github](https://github.com/aave/aave-v3-core/blob/master/contracts/mocks/oracle/PriceOracle.sol)                             | 0x8aA68Ca9e25aAb6f9f41bF341d12Ab407AE099E2 |

## Tokens

| Token                                  | Address                                    |
| -------------------------------------- | ------------------------------------------ |
| DAI-AToken-Avalanche (aDAI)            | 0x82E64f49Ed5EC1bC6e43DAD4FC8Af9bb3A2312EE |
| DAI-StableDebtToken-Avalanche (sDAI)   | 0xd94112B5B62d53C9402e7A60289c6810dEF1dC9B |
| DAI-VariableDebtToken-Avalanche (vDAI) | 0x8619d80FB0141ba7F184CbF22fd724116D9f7ffC |
| LINK-AToken-Avalanche (aLINK)          | 0x191c10Aa4AF7C30e871E70C95dB0E4eb77237530 |
| LINK-StableDebtToken-Avalanche         | 0x89D976629b7055ff1ca02b927BA3e020F22A44e4 |
| LINK-VariableDebtToken-Avalanche       | 0x953A573793604aF8d41F306FEb8274190dB4aE0e |
| USDC-AToken-Avalanche                  | 0x625E7708f30cA75bfd92586e17077590C60eb4cD |
| USDC-StableDebtToken-Avalanche         | 0x307ffe186F84a3bc2613D1eA417A5737D69A7007 |
| USDC-VariableDebtToken-Avalanche       | 0xFCCf3cAbbe80101232d343252614b6A3eE81C989 |
| WBTC-AToken-Avalanche                  | 0x078f358208685046a11C85e8ad32895DED33A249 |
| WBTC-StableDebtToken-Avalanche         | 0x633b207Dd676331c413D4C013a6294B0FE47cD0e |
| WBTC-VariableDebtToken-Avalanche       | 0x92b42c66840C7AD907b4BF74879FF3eF7c529473 |
| WETH-AToken-Avalanche                  | 0xe50fA9b3c56FfB159cB0FCA61F5c9D750e8128c8 |
| WETH-StableDebtToken-Avalanche         | 0xD8Ad37849950903571df17049516a5CD4cbE55F6 |
| WETH-VariableDebtToken-Avalanche       | 0x0c84331e39d6658Cd6e6b9ba04736cC4c4734351 |
| USDT-AToken-Avalanche                  | 0x6ab707Aca953eDAeFBc4fD23bA73294241490620 |
| USDT-StableDebtToken-Avalanche         | 0x70eFfc565DB6EEf7B927610155602d31b670e802 |
| USDT-VariableDebtToken-Avalanche       | 0xfb00AC187a8Eb5AFAE4eACE434F493Eb62672df7 |
| AAVE-AToken-Avalanche                  | 0xf329e36C7bF6E5E86ce2150875a84Ce77f477375 |
| AAVE-StableDebtToken-Avalanche         | 0xfAeF6A702D15428E588d4C0614AEFb4348D83D48 |
| AAVE-VariableDebtToken-Avalanche       | 0xE80761Ea617F66F96274eA5e8c37f03960ecC679 |
| WAVAX-AToken-Avalanche                 | 0x6d80113e533a2C0fe82EaBD35f1875DcEA89Ea97 |
| WAVAX-StableDebtToken-Avalanche        | 0xF15F26710c827DDe8ACBA678682F3Ce24f2Fb56E |
| WAVAX-VariableDebtToken-Avalanche      | 0x4a1c3aD6Ed28a636ee1751C69071f6be75DEb8B8 |