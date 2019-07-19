# Toolchain wrappers

This repository provides toolchain wrappers for Raspberry Pi (arm-linux-gnueabihf),
Android (armv7-linux-anroideabi, aarch64-linux-android), and iOS (86_64-apple-ios, aarch64-apple-ios)
toolchains through target prefixed commands for `gcc clang ld ld.gold nm ar ranlib cabal`.

The driver is the `wrapper` script. `bootstrap` generates the `<target>-<command>` symlinks to the
driver. While the `.config` files hold the relevant abstractions.

## Installation

To use `wrapper`, you must run `bootstrap` first.
