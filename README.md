# swoop-testing

This repo is intended to track the testing process of Swoop.

## Testing environments

| Domain     | Environment | Objective                    | Factory | Router | Deployed                |
| -----------| ----------- | --------------------------   | ------- | ------ | ----------------------- |
| P-OPS #1    | Testnet    | Liquidity provider testing   | 0x      | 0x     | 2020-10-23 xx:xx:xx UTC |
| P-OPS #2    | Testnet    | Repeat trade testing         | 0x      | 0x     | 2020-10-23 xx:xx:xx UTC |
| Swoop demo  | Testnet    | Free testing/no restrictions | 0x      | 0x     | 2020-10-23 xx:xx:xx UTC |

### P-OPS #1

P-OPS #1 is a testing environment dedicated for P-OPS to test liquidity provider features.

#### Prerequisites:

- No initial pools will be set up by the deployer.
- Testnet 10,000 ONE and 10,000 of each testnet token will be distributed by the deployer.

### P-OPS #2

P-OPS #2 is a testing environment dedicated for P-OPS to test repeated trading outcomes.

#### Prerequisites:

- Pool will be setup for all test token pairings by the deployer. Each pair will consist of 1,000,000 token x and 1,000,000 token y to simulate a similar pricing situation.
- 10,000 of testnet ONE and 10,000 of each testnet token will be distributed by the deployer.

### Swoop demo

Swoop demo is the general testing environment Harmony utilizes.

#### Prerequisites:

- Pool will be setup for all test token pairings by the deployer. Each pair will consist of 1,000,000 token x and 1,000,000 token y to simulate a similar pricing situation.
- 10,000 of testnet ONE and 10,000 of each testnet token will be distributed by the deployer.

## Bugs & issues

Please report any issues you run into while testing in this repository.

## Common issues/troubleshooting

If you happen to have issues loading the Swoop token list you can try to do what's detailed in the video below:
[Cache & Local storage reset](http://tools.harmony.one.s3.amazonaws.com/swoop-reset.mov)
