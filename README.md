# rustdoc-groff-man
Turns the json files generated by `rustdoc +nightly --output-format json` into man pages

## Quick Start
```console
~/some-rust-library$ cargo +nightly rustdoc --output-format json
~/some-rust-library$ rustdoc-groff-man ./target/doc/some-rust-library.json
~/some-rust-library$ man './man/some_rust_library.3'
```

