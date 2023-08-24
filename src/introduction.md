# Learning Bootcamp

Welcome to the teams repository of learning materials designed to give a intesive primer to all the topics and technologies we prefer to use.

## How to use this book

This is not intended as an exhaustive guide to each technology but more a focused primer to each teachnology its purpose and when to use it. We will provide links for further reading for each topic.

The repo is built with mdbook and can be viewd on the github pages site or built locally with `mdbook build` or `mdbook serve`

## Local development

This book is built with [mdbook](https://rust-lang.github.io/mdBook/index.html) so development requires running `mdbook serve`

To install mdbook you first need `cargo` from [rustup](https://rustup.rs/) then install `mdbook` with `cargo install mdbook`

To develop this repo run `mdbook serve`, the book will be served on `http://localhost:3000`.

To add to the book focus entirely on the `SUMMARY.md`. Adding to this file will auto generate the markdown files if `mdbook serve` is running.
