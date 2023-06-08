# Optimus

Numerical definitions for creating and using first-order optimization techniques based on the [Optax](https://github.com/deepmind/optax) library.

Here is a non-exhaustive list of supported optimizers:

* Adabelief
* Adagrad
* Adam
* Adamw
* Fromage
* Lamb
* Noisy SGD
* Radam
* RMSProp
* SGD
* Yogi

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `optimus` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:optimus, "~> 0.1"}
  ]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at <https://hexdocs.pm/optimus>.
