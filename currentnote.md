# Easy way to use iex

```elixir
# this will start iex with loaded external dependencies
iex -S mix

# this will compile a script
> c("test1.exs")

# this will run test() in module Test1
> Test1.test()
```

# Connect nodes

```elixir
# this will start an iex with a name
iex --sname one

# this will connect to another node
Node.connect :'two@abc'
```
