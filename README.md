# codingame_rust_stub

Rust stub project configured based on [Languages Versions](https://www.codingame.com/playgrounds/40701/help-center/languages-versions) documentation as of January 2023.

Verify the expected version:

```bash
$ rustup show
```

Execute the app as debug and release respectively:

```bash
cargo run
cargo run --release
```

## rust-toolchain

The [rust-toolchain.toml](./rust-toolchain.toml) specifies the Rust version.

```toml
[toolchain]
channel = "1.60.0"
```

Documentation links:

- [Rust release announcement](https://blog.rust-lang.org/2022/04/07/Rust-1.60.0.html)
- [Rust release notes](https://github.com/rust-lang/rust/blob/master/RELEASES.md#version-1600-2022-04-07)
- [rust-toolchain overrides](https://rust-lang.github.io/rustup/overrides.html)

## Cargo Dependencies

The [Cargo.toml](./Cargo.toml) specifies the libraries and versions.

```toml
[package]
name = "codingame_rust_stub"
version = "0.1.0"
edition = "2021"

[dependencies]
chrono = "0.4.19"
itertools = "0.10.0"
libc = "0.2.93"
rand = "0.8.3"
regex = "1.4.5"
time = "0.2.26"
```
Documentation links:

- [chrono](https://docs.rs/chrono/0.4.19/chrono/index.html)
- [itertools](https://docs.rs/itertools/0.10.0/itertools/index.html)
- [libc](https://docs.rs/libc/0.2.93/libc/index.html)
- [rand](https://docs.rs/rand/0.8.3/rand/index.html)
- [regex](https://docs.rs/regex/1.4.5/regex/index.html)
- [time](https://docs.rs/time/0.2.26/time/index.html)

## License

[Unlicense](./LICENSE).
