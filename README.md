## Hello World Rust Iced

## Requirements for Debian
```
sudo apt-get install gcc-arm-linux-gnueabihf gcc-mingw-w64 git wget make libgtk-4-dev libssl-dev pkg-config curl gcc-mingw-w64-x86-64 g++-mingw-w64-x86-64 wine64
rustup target add x86_64-pc-windows-gnu i686-pc-windows-gnu x86_64-apple-darwin x86_64-unknown-netbsd
```


The classic counter example explained in the [`README`](../../README.md).

The __[`main`]__ file contains all the code of the example.

<div align="center">
  <img src="https://iced.rs/examples/counter.gif">
</div>

You can run it with `cargo run`:
```
cargo run --package counter
```

Build Windows32 Binary
```
make windows32
```

Build Windows64 Binary
```
make windows64
```

