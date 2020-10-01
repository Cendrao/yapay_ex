# YapayEx

A SDK to communicate with yapay API, to create/see orders.

[![CircleCI](https://circleci.com/gh/paulo-silva/yapay_ex.svg?style=shield)](https://circleci.com/gh/paulo-silva/yapay_ex)

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `yapay_ex` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:yapay_ex, "~> 0.1.0"}
  ]
end
```

### Creating an order

```elixir
YapayEx.create_order(%Order{})
```

