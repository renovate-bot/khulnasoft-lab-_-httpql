# HTTPQL

[<img alt="github" src="https://img.shields.io/badge/github-khulnasoft/httpql-8da0cb?style=for-the-badge&labelColor=555555&logo=github" height="20">](https://github.com/khulnasoft-lab/httpql)
[<img alt="crates.io" src="https://img.shields.io/crates/v/httpql?color=fc8d62&logo=rust&style=for-the-badge" height="20">](https://crates.io/crates/httpql)

This is the Rust parser for the [HTTPQL language](https://docs.khulnasoft.com/internals/httpql.html).

```rust
use httpql::HTTPQL;

pub fn main() {
  let query = HTTPQL::parse(r"req.ext.cont:"HELLO"").unwrap();
  println("Query is {}", query);
}
```
