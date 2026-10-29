# chessroller-releases

Release artifacts for [ChessRoller](https://chessroller.com): the installers, and the `latest*.yml`
update feeds the app's auto-updater reads. Downloads are on
the [releases page](../../releases).

Which file you want:

- **macOS** (Apple Silicon): `ChessRoller-<version>-arm64.dmg`
- **Windows x64**: `ChessRoller-<version>-x64.exe`
- **Windows ARM64**: `ChessRoller-<version>-arm64.exe`
- **Linux x64** (beta): `ChessRoller-<version>-x86_64.AppImage`
- **Linux ARM64** (beta): `ChessRoller-<version>-arm64.AppImage`

On Linux, make the AppImage executable (`chmod +x ChessRoller-*.AppImage`) and
run it. It needs glibc 2.28 or newer (Ubuntu 20.04, Debian 11, Fedora 29 or
later).

The `-mac.zip` and `.blockmap` files are for the in-app updater, not for
downloading by hand.

## About the "Source code" links

This repository contains no source code, only the files above. GitHub attaches
"Source code (zip)" and "Source code (tar.gz)" to every release automatically,
generated from the release tag, and offers no way to disable them. On a release
here they contain just this README.
