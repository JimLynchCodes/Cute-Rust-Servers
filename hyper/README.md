First, scaffold a vanilla cargo project:
```
cargo new hello-kitten
```

Navigate into the new directory.

add hyper to bottom of Cargo.toml:
```
rocket = "0.4.5"
```

Replace main.rs with the script [here](https://docs.rs/rocket/0.4.5/rocket/).

Then run the server:
```
cargo run
```

Then hit the server at http://localhost:8000/