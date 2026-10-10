# interactor-aria-patrol-client

An Elixir client that connects to the Spatial Node Store server and walks an entity along a patrol route.

## What it is for

The client orders its waypoints by nearest neighbour and sends movement intents over ENet, so the server stays authoritative over where the entity is. It also carries a locomotion test bot and the HDDL domains and problems its fixtures are generated from.

## Build and run

```sh
mix deps.get
mix patrol.run
```

`mix help patrol.run` and `mix help test.locomotion` list the options.

## Licence

MIT. See [LICENSE](LICENSE).
