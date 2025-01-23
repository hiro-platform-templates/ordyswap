# Ordinals Swap

Demonstrates trustless atomic swaps between Ordinals and Stacks. 

## Know your Contract

For more details about this protocol in Stacks, please refer to [Mechanism's Ordyswap](https://github.com/mechanismHQ/ordyswap) project.

The [ord-swap.clar](/examples/ordyswap/contracts/ord-swap.clar) contract includes the following functionality.

+ `validate-offer-transfer` function validates the transfer of an Ordinal
+ `finalize-offer` finalizes the transfer offer
+ `cancel-offer` function can be used to cancel a pending offer
+ `refund-cancelled-offer` function is used to refund a canceled offer back to the owner

To add new contracts, use [Clarinet](https://docs.hiro.so/stacks/clarinet).

## Test your Contract

+ You can manually test your your contracts in the [Clarinet console](https://docs.hiro.so/clarinet/how-to-guides/how-to-test-contract#load-contracts-in-a-console).
+ You can programmatically test your contracts with [unit tests](https://docs.hiro.so/clarinet/how-to-guides/how-to-test-contract).

