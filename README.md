# NJS's Rust Library Template

A nice and simple Rust Library template to let me (or anyone else)
quickly whip up new projects.

## Features

- Some basic settings for rustfmt, and the default settings for Clippy.
- [log](https://docs.rs/log/latest/log/) for logging
- [anyhow](https://crates.io/crates/anyhow) for error context

Every project is different, so there's not many dependencies in this template.
This is mainly a quick way to get started.
If you're not sure what you need, check out
[Awesome Rust](https://github.com/rust-unofficial/awesome-rust)
for more useful crates and libraries.

### VS Code Extensions

- [Rust Analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)
- [Better TOML](https://marketplace.visualstudio.com/items?itemName=bungcip.better-toml)
- [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)
with some basic settings.
- [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
- [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
- [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)
- [Git Graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph)

## Installation

You can download this repo as a .zip or clone it with git,
but a cleaner approach is with [degit](https://github.com/Rich-Harris/degit).

```bash
npx degit njs-templates/njs-rust-lib new-project
cd new-project
cargo build
```

## Recommended IDE

This was meant to be used with VS Code, but it should work with any editor.
You'll be prompted to install any recommended extensions that aren't installed.
If no one on your team is using VS Code, just delete the `.vscode/` folder.

## Next steps

- [ ] Run `cargo run` to build the project and make sure everything's working.
- [ ] Delete `LICENSE.txt` from the root of the directory.
    - If your project still uses an MIT License, just edit the author and year.
- [ ] Either delete `CHANGELOG.md` or remove its contents.
- [ ] In `Cargo.toml`, change the project name and version.
- [ ] Delete the `.git/` folder if you cloned this repo.
- [ ] Run a `git init` to start tracking changes.
- [ ] Do whatever. This code is yours now. Credit is appreciated but not needed.

Optional but recommended

- [ ] Install [cargo edit](https://github.com/killercup/cargo-edit)
for nicer dependency management.
- [ ] Install [cargo audit](https://docs.rs/cargo-audit/latest/cargo_audit/)
for better dependency security.
- [ ] Using cargo edit, update outdated dependencies with `cargo upgrade`.
- [ ] Using cargo edit, remove any unwanted dependencies with `cargo rm`.
- [ ] Check out [Awesome Rust](https://github.com/rust-unofficial/awesome-rust)
for more useful crates and libraries.

```bash
cargo install cargo-edit cargo-audit
cargo upgrade
```
