# rust

### libraries installed
NOTE: Installation is done using the official rust website. https://www.rust-lang.org/learn/get-started

```
info: latest update on 2024-04-09, rust version 1.77.2 (25ef9e3d8 2024-04-09)
info: downloading component 'cargo'
info: downloading component 'clippy'
info: downloading component 'rust-docs'
 14.9 MiB /  14.9 MiB (100 %)  14.3 MiB/s in  1s ETA:  0s
info: downloading component 'rust-std'
 22.9 MiB /  22.9 MiB (100 %)  14.2 MiB/s in  1s ETA:  0s
info: downloading component 'rustc'
 54.1 MiB /  54.1 MiB (100 %)  14.2 MiB/s in  3s ETA:  0s
info: downloading component 'rustfmt'
info: installing component 'cargo'
info: installing component 'clippy'
info: installing component 'rust-docs'
 14.9 MiB /  14.9 MiB (100 %)   5.4 MiB/s in  2s ETA:  0s
info: installing component 'rust-std'
 22.9 MiB /  22.9 MiB (100 %)  19.6 MiB/s in  1s ETA:  0s
info: installing component 'rustc'
 54.1 MiB /  54.1 MiB (100 %)  22.6 MiB/s in  2s ETA:  0s
info: installing component 'rustfmt'
```


Rust is installed now. Great!

To get started you may need to restart your current shell.
This would reload your PATH environment variable to include
Cargo's bin directory ($HOME/.cargo/bin).

To configure your current shell, you need to source
the corresponding env file under $HOME/.cargo.

This is usually done by running one of the following (note the leading DOT):
. "$HOME/.cargo/env"            # For sh/bash/zsh/ash/dash/pdksh
source "$HOME/.cargo/env.fish"  # For fish
