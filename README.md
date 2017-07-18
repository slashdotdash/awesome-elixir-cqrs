# Awesome Elixir and CQRS [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome Elixir, Command Query Responsibility Segregation (CQRS) and event sourcing resources.

## Contents

- [Libraries](#libraries)
- [Books](#books)
- [Articles](#articles)
- [Presentations](#presentations)
- [Example applications](#example-applications)

---

## Libraries

- [Commanded](https://github.com/slashdotdash/commanded) - Use Commanded to build your own Elixir applications following the CQRS/ES pattern. Provides support for command registration and dispatch, hosting and delegation to aggregate roots, event handling, and long running process managers.

- [Commanded audit middleware](https://github.com/slashdotdash/commanded-audit-middleware) - Command auditing middleware for Commanded CQRS/ES applications using Ecto for persistence.

- [Commanded Ecto projections](https://github.com/slashdotdash/commanded-ecto-projections) - Read model projections for Commanded using Ecto.

- [EventStore](https://github.com/slashdotdash/eventstore) - An Elixir event store using Postgres for persistence.

- [EventStore migrator](https://github.com/slashdotdash/eventstore-migrator) - Copy & transform migration strategy for EventStore.

- [Extreme](https://github.com/exponentially/extreme) - Elixir Adapter for Greg Young's [EventStore](https://geteventstore.com/).

## Books

- [Building Conduit](https://leanpub.com/buildingconduit) - Applying CQRS/ES to an Elixir and Phoenix web app.

## Articles

- [Building a CQRS/ES web application in Elixir using Phoenix](https://10consulting.com/2017/01/04/building-a-cqrs-web-application-in-elixir-using-phoenix/) - Case study describing how a web application was built following a Command Query Responsibility Segregation and event sourcing pattern.

## Presentations

- [Building CQRS/ES web applications in Elixir using Phoenix](https://10consulting.com/2017/03/23/building-cqrs-web-applications-in-elixir/) - Discover how to build applications following domain-driven design principles, using the CQRS/ES pattern with Elixir and Phoenix.

## Example applications

- [Conduit](https://github.com/slashdotdash/conduit) - A blogging platform, an exemplary Medium.com clone, built as a Phoenix web application.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Ben Smith](mailto:ben@10consulting.com) has waived all copyright and related or neighbouring rights to this work.
