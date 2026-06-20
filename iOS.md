# iOS
This section lists the commands to run to build a sable_rapier.dylib for iOS.

### Requirements
* A MacOS machine
* An Apple Developer license (free)
* XCode and XCode Command line tools installed
* An iOS SDK installed through XCode
* Rust installed

## Initial Setup
1. Clone the repo
2. Navigate to `sable_rapier/src/main/rust`
3. Run `rustup toolchain install nightly`
4. Run `rustup target add aarch64-apple-ios --toolchain nightly`

> Note: You can execute the commands from step 3 and 4 after the initial setup to update rust and dependencies

## Build
Run `cargo build --release --target aarch64-apple-ios -p sable_rapier`
