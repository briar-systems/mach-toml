# mach-toml

<p>
  <a href="https://github.com/briar-systems/mach-toml/actions/workflows/ci.yml"><img src="https://github.com/briar-systems/mach-toml/actions/workflows/ci.yml/badge.svg" alt="CI"></a>
  <a href="LICENSE"><img src="https://img.shields.io/github/license/briar-systems/mach-toml?color=FF00FF&labelColor=000000" alt="License"></a>
</p>

**A Mach library for reading TOML 1.0.**

## Usage

Add the dependency to `mach.toml`:

```toml
[dep.toml]
git = "https://github.com/briar-systems/mach-toml"
ref = "branch/dev"
```

Then import each module by its source path in the package:

```mach
use toml.lookup;
use toml.parse;
use toml.tree;
```

`parse.parse` reads a TOML 1.0 document into a table owned by an allocator, `lookup.get_*` reads values by dotted path, and `tree.dnit` releases the table. The value types are in `toml.value` and the parse error is `toml.error.TomlError`.


## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for building, testing and the contribution rules.


## License

[MIT](LICENSE)
