# chessroller-releases

Release artifacts for ChessRoller: the installers, and the `latest.yml` /
`latest-mac.yml` update feeds the app's auto-updater reads. Downloads are on
the [releases page](../../releases).

Which file you want:

- **macOS** (Apple Silicon): `ChessRoller-<version>-arm64.dmg`
- **Windows x64**: `ChessRoller-<version>-x64.exe`
- **Windows ARM64**: `ChessRoller-<version>-arm64.exe`

The `-mac.zip` and `.blockmap` files are for the in-app updater, not for
downloading by hand.

## About the "Source code" links

This repository contains no source code, only the files above. GitHub attaches
"Source code (zip)" and "Source code (tar.gz)" to every release automatically,
generated from the release tag, and offers no way to disable them. On a release
here they contain just this README.
