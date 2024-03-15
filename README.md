# Aural

A small, lightweight translator app built on modern web technologies.

## How to use

We recommend installing this project directly via the binaries provided on our [release page](https://github.com/couscousdude/aural/releases) once the app is stable. If you would like to compile it yourself from source, follow the instructions below.

## Running in development

To run in development, you need the following prerequisites:

- Rust (`cargo` and `rustc`). We recommend using `rustup` to install Rust.
- `pnpm` and `node` (for installing frontend dependencies and creating the development server)

After cloning the repository for the first time, run `pnpm install` to install all of the dependencies you need. The Rust dependencies will be handled automatically by Tauri.

To start the development server, with features like hot reload on save, run `pnpm tauri dev`. This may take a while the first time while it installs Rust dependencies via Cargo.

To create a production build, run `pnpm tauri build`. Depending on your PC specs, this may take a bit of time while it compiles the Rust crates for production.
