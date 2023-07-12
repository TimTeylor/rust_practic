# rust_practic
This repository contains Rust projects that I wrote during my internship. Each project is in its own branch

## Automatic Formatting with rustfmt
The rustfmt tool reformats your code according to the community code style. Many collaborative projects use rustfmt to prevent arguments about which style to use when writing Rust: everyone formats their code using the tool.
```
cargo fmt
```

## Fix Your Code with rustfix
The rustfix tool is included with Rust installations and can automatically fix compiler warnings that have a clear way to correct the problem that’s likely what you want.
```
cargo fix
```

## More Lints with Clippy
The Clippy tool is a collection of lints to analyze your code so you can catch common mistakes and improve your Rust code.
```
cargo clippy
```

## Dependency documentation
build documentation provided by all your dependencies locally and open it in your browser
```
cargo doc --open
```