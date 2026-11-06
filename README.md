# Session Board downloads

Session Board is a macOS app for managing Claude Code sessions. Requires macOS 14 or later; releases support Apple Silicon and Intel.

This repository hosts release downloads, release notes, and the automatic update feed. Application source code is maintained separately.

## Downloads

Download the signed, Apple-notarized app from the [latest release](https://github.com/jacobmorrin/session-board-releases/releases/latest).

Unzip the download, move **Session Board.app** into **Applications**, and open it. Claude Code must be installed separately. Existing users of older, locally built versions need to install an updater-enabled release once; future releases are available from **Session Board → Check for Updates…**.

## Automatic updates

Updater-enabled releases check the signed `appcast.xml` feed. Download archives and update metadata are signed with a separate update-signing key. Private keys and account credentials are never stored in this repository.

Checks are daily, and background downloads are optional. Session Board does not restart itself without your choice. A local source build does not automatically replace itself with a downloaded release.

Session Board is independent and is not affiliated with Anthropic.
