# farcolorer-rust

**Important**: this schema has now found its permanent place in the official Colorer repo, please open pull requests there: https://github.com/colorer/Colorer-schemes/blob/master/hrc/hrc/base/rust.hrc

Rust syntax schema for FarColorer plugin.

This schema is far from complete (but so is the documented [Rust 1.0.0-beta.2 grammar specification](http://doc.rust-lang.org/1.0.0-beta.2/grammar.html)). Nevertheless this schema already works better than what FarColorer picks by default, which is C++ syntax, I believe. This schema highlights the right keywords and doesn't freak out from single apostrophe inside angle brackets ("lifetime parameter"?).

To install into your Far, copy `proto.hrc` and `types\rust.hrc` into `Plugins\FarColorer\base\hrc\auto` under your Far Manager directory.

To update plugin settings in Far, open some file for editing, press F11 > "FarColorer" > "Reload schema library".

Pull requests are welcome. If you see broken highlighting, feel free to open an issue with sample code.

I'll contact FarColorer maintainers to push the schema to the official repo in future.

Blog post: http://yacoder.net/blog/2015/04/29/rust-syntax-highlighter-for-far-colorer/

## Before

![before](http://yacoder.net/blog/wp-content/uploads/2015/04/rust_before.png)

## After

![after](http://yacoder.net/blog/wp-content/uploads/2015/04/rust_after.png)
