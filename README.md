# homebrew-tap

Homebrew tap for [lohost](https://lohost.dev), the menu-bar app that shows every
server on your Mac, whose it is, and what it’s doing.

```sh
brew install --cask lohost-dev/tap/lohost
```

Homebrew adds the tap on the way. The cask installs the notarized DMG for your
Mac’s architecture from dl.lohost.dev and links the `lohost` command onto your
PATH. The app updates itself; `brew upgrade` is not needed.

To remove everything lohost kept: `brew uninstall --zap --cask lohost`.

Casks/lohost.rb is written by lohost’s release script on every stable release.
Issues belong in [lohost-dev/lohost](https://github.com/lohost-dev/lohost/issues).
