# Aspire plugin

Installs the [Microsoft Aspire](https://aspire.dev) CLI through [proto](https://moonrepo.dev/proto).

## Usage

Import the plugin in `.prototools`:

```toml
[plugins.tools]
aspire = "https://raw.githubusercontent.com/id6tm/proto-plugins/master/aspire/plugin.toml"
```

Then pin Aspire for the project:

```sh
proto pin aspire latest --resolve
```

Install the pinned version:

```sh
proto install
```

Run the CLI:

```sh
aspire --help
```
