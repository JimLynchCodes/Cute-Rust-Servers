
First, use "nightly" Rust version as described [here](https://rocket.rs/v0.4/guide/getting-started/):
```
rustup override set nightly
```

Then scaffold a vanilla cargo project:
```
cargo new hello-kitten
```

Navigate into the new directory.

add rocket to bottom of Crago.toml:
```
rocket = "0.4.5"
```

Replace main.rs with the script [here](https://docs.rs/rocket/0.4.5/rocket/).

Then run the server:
```
cargo run
```