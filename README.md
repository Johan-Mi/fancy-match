# fancy-match

Apply the `#[fancy_match]` attribute to a match expression to let string
literals match anything that implements `PartialEq<str>`.

This requires a nightly compiler version.

Note: if you only care about matching `String`s, use
`#![feature(string_deref_patterns)]` instead.
