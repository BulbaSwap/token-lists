# Bulbaswap token lists

Official token list of [Bulbaswap](https://bulbaswap.io).

## How to Add a Token

1. Fork the repo so that you can push edits to a version of this repo that you have write permissions to. See [docs](https://docs.github.com/en/get-started/quickstart/fork-a-repo) for more details.
2. Clone the repo. See [docs](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) for more details.
3. Enter the repo via `cd token-lists`.
4. Add your token's logo to `assets/<network>/<token address>/logo.svg` (it must be a SVG). The token address must be in lowercase.
5. Add your token to `tokens/<network>/list.json`, where `<network>` is the name of the network your token is deployed to.
6. Submit a pull request.
