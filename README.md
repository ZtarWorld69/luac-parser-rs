
[![crates.io](https://img.shields.io/crates/v/luac-parser.svg)](https://crates.io/crates/luac-parser)
[![docs.rs](https://docs.rs/luac-parser/badge.svg)](https://docs.rs/luac-parser)


# luac-parser (in English)

lua bytecode parser, currently support lua51, lua52, lua53, lua54, luajit, luau

This is part of [metaworm's luadec][luadec], which is the best lua decompiler at present

You can write your custom luac parser based on this code, which can be able to compiling to WASM and loaded by [metaworm's luadec][luadec], to decompile the unofficial lua bytecode

[luadec]: http://luadec.metaworm.site
[nom]: https://github.com/rust-bakery/nom

Thanks to the flexibility of [nom][nom], it is very easy to write your own parser in rust, read [this article][write-parser] to learn how to write a luac parser

[luadec]: http://luadec.metaworm.site
[nom]: https://github.com/rust-bakery/nom
[write-parser]: https://github.com/metaworm/luac-parser-rs/wiki/Write-custom-luac-parser
