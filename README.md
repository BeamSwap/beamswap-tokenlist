# beamswap-tokenlist

### Whitelisting instructions

- Fork this repo
  ```
  gh repo clone beamswap/beamswap-tokenlist
  ```
- Create a folder under *assets/chains/{blockchainName}/{tokenAddress}*
- Add token's icon (logo.png) under the folder created in the previous step
- Add token's info in the *tokenlist.json* file, in this format:
  ```
  {
      "name": [token_name],
      "address": [token_address],
      "symbol": [token_symbol],
      "decimals": [token_decimals],
      "chainId": 1285,
      "logoURI": "https://raw.githubusercontent.com/BeamSwap/beamswap-tokenlist/main/assets/chains/[blockchainName]/[token_address]/logo.png"
  }
  ```
- Make a Pull Request to this repo including all of the above.

<br>

More info about pull requests:
- [Creating a pull request from a fork](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork)
