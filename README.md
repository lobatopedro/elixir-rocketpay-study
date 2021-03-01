# Rocketpay

To start your Phoenix server:

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.setup`
  * Start Phoenix endpoint with `mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](https://hexdocs.pm/phoenix/deployment.html).

## Learn more

  * Official website: https://www.phoenixframework.org/
  * Guides: https://hexdocs.pm/phoenix/overview.html
  * Docs: https://hexdocs.pm/phoenix
  * Forum: https://elixirforum.com/c/phoenix-forum
  * Source: https://github.com/phoenixframework/phoenix

## Course Description
Payment API study

## Resources
- Create users and accounts
- Deposit
- Withraw
- Transactions

## Dependencies used
```
defp deps do
  [
    # ...default deps
    {:credo, "~>1.5", only: [:dev, :test], runtime: false},
    {:bcrypt_elixir, "~> 2.0"},
    {:decimal, "~>2.0"},
    {:excoveralls, "~> 0.10", only: :test}
  ]
end
```
