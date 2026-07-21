# vc-x1-bot-repo-template

This is the bot repo of a dual-repo convention for using
a bot to help in the development of a coding project. The goal
is that this bot repo contains the "why" and "how", while the
partner main repo contains the "what". The key to the convention
is each change is cross-referenced to the other. Thus there
is a coherent story of the development of the project across time.

This repo is the source template for the bot side:
[vc-x1](https://github.com/winksaville/vc-x1) `init` copies its
contents — the licenses, this README.md, and the empty
`memory/MEMORY.md` — into a new project's `.claude` repo, then
generates the remaining minimum files (such as `.vc-config.toml`)
itself. `memory/MEMORY.md` is intentionally empty and expected to
stay empty; it is seeded here because Claude tends to create it
otherwise.

See [vc-x1-work-repo-template](https://github.com/winksaville/vc-x1-work-repo-template)
for more details.

## License

Licensed under either of

- Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE) or http://apache.org/licenses/LICENSE-2.0)
- MIT license ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

### Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall
be dual licensed as above, without any additional terms or conditions.
