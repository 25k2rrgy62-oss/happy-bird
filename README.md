# Happy Bird

A pixel-art flappy game for Android and iPhone, with Classic, Easy and Chaos modes, online Versus, bots, daily missions and a shop.

- **Download:** [latest release](https://github.com/25k2rrgy62-oss/happy-bird/releases/latest) (`HappyBird.apk` for Android, `HappyBird.ipa` for iPhone, unsigned)
- **What's new:** [CHANGELOG.md](CHANGELOG.md)
- **Test versions:** versions ending in `-alpha` or `-beta` are on the [Releases page](https://github.com/25k2rrgy62-oss/happy-bird/releases) marked "Pre-release". They don't replace the latest finished version.

## How it's built
The whole game is `index.html`. The version number is the `app-version` line near its top.
Every push that changes it runs `.github/workflows/build.yml`, which builds both apps with Capacitor
and publishes them on a release named after the version, with that version's changelog as the notes.
