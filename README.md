# homebrew-tap

Install Harpertoken tools on Mac with Homebrew in Ruby.

## Formula

- `Formula/harper-ai.rb` - version 0.20.1, Apache-2.0
- Builds `harper` and `harper-batch` from source with Rust

## Start

```bash
brew tap harpertoken/homebrew-tap
brew install harper-ai
harper --help
```

## Update

Bump `version`, `url`, and `sha256` in `Formula/harper-ai.rb` for each release.

## Contribute

- Report: open an issue for install problems.
- Change: small pull requests preferred.
