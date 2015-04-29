# farcolorer-rust

Rust syntax schema for FarColorer plugin.

This schema is far from complete (but so is the documented [Rust 1.0.0-beta.2 grammar specification](http://doc.rust-lang.org/1.0.0-beta.2/grammar.html)). Nevertheless this schema already works better than what FarColorer picks by default, which is C++ syntax, I believe. This schema highlights the right keywords and doesn't freak out from single apostrophe inside angle brackets ("lifetime parameter"?).

To install into your Far:
* place the `proto.hrc` into `Plugins\FarColorer\base\hrc\auto` under your Far Manager directory;
* place the `rust.hrc` into `Plugins\FarColorer\base\hrc\auto\types` under your Far Manager directory.

To update plugin settings in Far:
* open some file for editing, press F11 > "FarColorer" > "Reload schema library".

Pull requests are welcome. Or if you see broken highlighting, feel free to open an issue with sample code.

I'll contact FarColorer maintainers to push the schema to the official repo in future.
