To Install Rust In Windows


go to: https://rust-lang.org/tools/install/

download .exe file based on 64bit architecture.

Run the file....
cmd will open (this was my contents of the cmd while I was installing Rust)

```bash
warn: It looks like you have an existing rustup settings file at:
warn: C:\Users\Anindya Roy\.rustup\settings.toml
warn: Rustup will install the default toolchain as specified in the settings file,
warn: instead of the one inferred from the default host triple.

Welcome to Rust!

This will download and install the official compiler for the Rust
programming language, and its package manager, Cargo.

Rustup metadata and toolchains will be installed into the Rustup
home directory, located at:

  C:\Users\Anindya Roy\.rustup

This can be modified with the RUSTUP_HOME environment variable.

The Cargo home directory is located at:

  C:\Users\Anindya Roy\.cargo

This can be modified with the CARGO_HOME environment variable.

The cargo, rustc, rustup and other commands will be added to
Cargo's bin directory, located at:

  C:\Users\Anindya Roy\.cargo\bin

This path will then be added to your PATH environment variable by
modifying the PATH registry key at HKEY_CURRENT_USER\Environment.

You can uninstall at any time with rustup self uninstall and
these changes will be reverted.

Current installation options:


   default host triple: x86_64-pc-windows-msvc
     default toolchain: stable (default)
               profile: default
  modify PATH variable: yes

1) Proceed with standard installation (default - just press enter)
2) Customize installation
3) Cancel installation
>

info: profile set to default
info: default host triple is x86_64-pc-windows-msvc
info: syncing channel updates for stable-x86_64-pc-windows-msvc
info: latest update on 2026-04-16 for version 1.95.0 (59807616e 2026-04-14)
info: downloading 6 components
        cargo installed                        9.54 MiB
       clippy installed                        3.80 MiB
    rust-docs installed                       21.19 MiB
     rust-std installed                       21.05 MiB
        rustc installed                       68.26 MiB
      rustfmt installed                        2.47 MiB                                                                                                     info: default toolchain set to stable-x86_64-pc-windows-msvc

  stable-x86_64-pc-windows-msvc installed - (timeout reading rustc version)


Rust is installed now. Great!

To get started you may need to restart your current shell.
This would reload its PATH environment variable to include
Cargo's bin directory (%USERPROFILE%\.cargo\bin).

Press the Enter key to continue.

```


To check the installation: 
1. Run: rustc --version
2. Run: cargo --version


