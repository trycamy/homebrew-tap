# Homebrew tap for camy

```bash
brew tap trycamy/tap
brew install camy
```

The one-line form, `brew install trycamy/tap/camy`, taps and installs in a
single step.

Installs the `camy` command with shell completions and man pages. Upgrade with:

```bash
brew upgrade camy
```

`Formula/camy.rb` is written by this repository's own workflow whenever a new
version reaches the release channel. The workflow verifies the version's signed
checksum manifest, then records the per-platform tarball URLs and SHA-256 values
from it. Nothing here is edited by hand.

Questions about the CLI itself belong at
[trycamy/cli](https://github.com/trycamy/cli).
