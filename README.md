# FulecoRafa/homebrew-tap

Homebrew tap for [Fuchico](https://github.com/FulecoRafa/fuchico), a notes
editor with Helix modal editing.

```sh
brew trust FulecoRafa/tap
brew install --cask FulecoRafa/tap/fuchico
```

Homebrew refuses casks from third-party taps until you `brew trust` them.
The app is unsigned; the cask clears the quarantine flag after install.

`Casks/fuchico.rb` is updated by `scripts/release.mjs` in the Fuchico repo on
every release.
