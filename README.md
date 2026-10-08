# mach-toml

<p>
  <a href="https://github.com/briar-systems/mach-toml/actions/workflows/ci.yml"><img src="https://github.com/briar-systems/mach-toml/actions/workflows/ci.yml/badge.svg" alt="CI"></a>
  <a href="LICENSE"><img src="https://img.shields.io/github/license/briar-systems/mach-toml?color=FF00FF&labelColor=000000" alt="License"></a>
</p>

**A Mach library for TOML reading and writing.**

## Usage

Add the dependency to `mach.toml`:

```toml
[dep.toml]
git = "https://github.com/briar-systems/mach-toml"
version = "^0.1"
```

Then bind the library in a source file:

```mach
use toml;
```


## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for building, testing and the contribution rules.


## License

[MIT](LICENSE)
