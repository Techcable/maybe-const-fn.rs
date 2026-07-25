# maybe-const-fn
<!-- cargo-rdme start -->

Macro to make a function as `const` based on a cfg flag

**WARNING**: Using this crate is generally discouraged.

Prefer using dtonlay's [`rustversion`] proc-macro where possible.
It is more robust and has no dependencies (no `syn` or `proc-macro2`).

The only advantage only advantage is that this crate is a declarative macro.
This crate mainly exists for backwards compatibility with old versions of [`rustversion-detect`].
Do not use this crate unless you know you need it.

[`rustversion`]: https://github.com/dtolnay/rustversion
[`rustversion-detect`]: https://github.com/Techcable/rustversion-detect/

<!-- cargo-rdme end -->

## License
Licensed under either of <a href="LICENSE-APACHE">Apache License, Version
2.0</a> or <a href="LICENSE-MIT">MIT license</a> at your option.

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in this crate by you, as defined in the Apache-2.0 license, shall
be dual licensed as above, without any additional terms or conditions.
