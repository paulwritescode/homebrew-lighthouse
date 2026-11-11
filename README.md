# Lighthouse Homebrew tap

Install the [Lighthouse local memory CLI](https://lighthouse.ovenplatform.com) on macOS with one command:

```sh
brew install paulwritescode/lighthouse/lighthouse
```

The formula currently installs Lighthouse v0.7.0. It builds the CLI from the matching tagged release and declares Go as a build dependency. Homebrew installs that build dependency when needed.

To upgrade after a new formula is published:

```sh
brew upgrade paulwritescode/lighthouse/lighthouse
```

If Lighthouse runs as a startup service, run `lighthouse service restart` after upgrading. Use `lighthouse version` to check the installed version.

The short command `brew install lighthouse` installs a different project from Homebrew Core. Use the qualified command above to select this CLI.
