# Hardhat Upgrades

Playing with proxy contracts to study how to do upgrades.

1. Upgrade Box -> BoxV2
2. Make a proxy contract that iniitally points to Box, and then have it point to BoxV2


Options
1. Deploy a proxy manually
2. Use hardhat-deploy's built-in proxies (this exercise)
3. OpenZeppelin's upgrades plugin (see Pat Collin's github repo hardhat-upgrades-fcc)