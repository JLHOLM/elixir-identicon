# Identicon for Elixir

Identicon is a Hex package that can be used to generate Identicons, a form of avatar, like the ones on GitHub.

To generate a new Identicon:
```elixir
Identicon.main("elixir")
```
This will generate a new Identicon with the filename "elixir.png" within your root directory. "elixir" can be replaced with any string, often times usernames or first names are used to generate the needed hash-value for the unique Identicon.

&nbsp;

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `identicon` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [{:identicon, "~> 0.1.0"}]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/identicon](https://hexdocs.pm/identicon).
