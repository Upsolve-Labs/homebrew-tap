# Upsolve Homebrew tap

```bash
brew install upsolve-labs/tap/upsolve
```

Installs the [Upsolve CLI](https://github.com/Upsolve-Labs/upsolve-cli), the
command line client for the Upsolve API. Upgrade with `brew upgrade upsolve`.

`Formula/upsolve.rb` is written by the CLI's release workflow on every release,
against the tarball published to npm as `@upsolve-labs/cli`. Do not edit it by
hand: the next release overwrites it. Change `scripts/homebrew-formula.ts` in
the CLI repository instead.
