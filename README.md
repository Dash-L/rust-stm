# Building

You should just be able to run `cargo build --release`.

# Running

* This project is setup to work with the NUCLEO-H753ZI STM32H7 development board, changes need to be made in `Cargo.toml`, `.cargo/config.toml`, and potentially `rust-toolchain.toml` (if the chip architecture changes) to use a different board.
* You should have the micro-usb cable plugged into the STLINK port on the NUCLEO board
* You must have [probe-rs](https://probe.rs/) installed. Then run `cargo run --release` (note that this also builds, so building prior to running is not neccesary).
