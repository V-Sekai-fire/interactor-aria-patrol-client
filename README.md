# interactor-aria-patrol-client

An Elixir client that connects to the Spatial Node Store server and walks an entity along a planned patrol route.

## What it is for

The client plans a route through its waypoints with `aria_patrol_solver` and sends movement intents over ENet, so the server stays authoritative over where the entity is. It also carries a locomotion test bot and the HDDL domains and problems its fixtures are generated from.

## Build and run

```sh
mix deps.get
mix patrol.run
```

`mix help patrol.run` and `mix help test.locomotion` list the options.

## Licence

The repository does not state a licence.
