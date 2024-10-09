# Unofficial Apollo homebrew taps
This is an unofficial homebrew tap for the low-latency desktop and game streaming server [Apollo](https://github.com/ClassicOldSong/Apollo/). It is intended to provide a way to install the latest beta version of Apollo for MacOS users.

### Add the repo

```bash
brew tap JeffSchofield/apollo
```

### Install the latest beta version

```bash
brew install apollo-beta --with-docs-off
```
**Note:** The `--with-docs-off` flag is required to avoid a build error. This is because there is currently an issue with the way the documentation is generated.

### Test

```bash
brew test apollo-beta
```
