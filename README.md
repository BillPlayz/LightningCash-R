Lightning Cash Core with 21M Supply and Yespower
===========================================

What is Lightning Cash?
----------------------

Lightning Cash is a cryptocurrency with the following key features:

- Maximum Supply: 21 million coins
- Mining Algorithm: Yespower POW (CPU-only)
- Block Time: 10 minutes
- Block Reward: 50 coins initially, halving every 210,000 blocks (~4 years)
- Address Format: Uses Bitcoin-style addresses

This is a new implementation focused on:
- Fair distribution through CPU mining
- Limited supply similar to Bitcoin's model
- Yespower algorithm for ASIC resistance

Technical Details
---------------
- Mining Algorithm: Yespower POW algorithm    ( CPU only )
- Difficulty: Adjusts every 2016 blocks (modified Dash's DarkGravityWave v3 algorithm, changes difficulty every block, and progressively lowers difficulty if long stale tips happens. )
- Initial Block Reward: 1.25 LightningCash
- Halving Schedule: Every 8.400.000 blocks ( +- 2 years 9 months and 17 days )
- Total Supply: 21 million coins

Building
--------
To build Lightning Cash Core, follow the build instructions in:
doc/build-*.md

For Any OS build instructions:
https://github.com/YourRepo/LightningCash/blob/master/doc/build-ALL-OS.md

License
-------
Lightning Cash Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process
-------------------
You can fork the repository, make improvements and create pull requests for bug fixes or enhancements.

Testing
-------
Testing is done privately before releasing new wallet versions.