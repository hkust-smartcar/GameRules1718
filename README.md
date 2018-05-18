# Smart Car 1718 Translated Game Rules

This repo contains the translated 13th Intelligent Car Racing Competition Game Rules. The files may be compiled into an HTML e-book using `mdbook` built with `rust`.

## Online Version

https://hkust-smartcar.github.io/GameRules1718/

## Releases

If you don't want to compile the book by yourself. Check out the latest [releases](https://github.com/hkust-smartcar/GameRules1718/releases).

## Compilation

Detailed instructions on [build - mdBook Documentation](https://rust-lang-nursery.github.io/mdBook/cli/build.html).

1.  Install the [Rust toolchain](https://www.rust-lang.org) and additionally the latest Microsoft Visual C++ Build Tools (which includes Windows SDK) if you are using Windows.
2.  Install `mdbook` using `cargo install mdbook` for the `cargo` command will be usable after installing Rust.
3.  Build the book using `mdbook build` at the repo's root directory. The generated book will appear within`/book/`.