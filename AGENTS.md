# AGENTS.md — hello_rust_iced

## What this is
The classic Iced (Rust GUI) counter example, set up to cross-compile for Windows 32/64-bit as well as run natively.

## Stack
- Rust
- Iced UI framework (`iced` 0.13.1)
- Cargo / Make

## Build
```bash
cargo run                       # run the counter app natively
make windows32                  # Windows 32-bit
make windows64                  # Windows 64-bit
```

## Run
```bash
cargo run --package counter
```

## Structure
- `src/main.rs` — the counter app code
- `Cargo.toml` — depends on `iced` (with `debug` feature)
- `index.html` — related demo page
- `Makefile` — build helpers

## Conventions
- No comments in code unless asked.
- Verify: `cargo check && cargo build`
