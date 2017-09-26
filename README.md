# Awesome Elixir and CQRS [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome Elixir, Command Query Responsibility Segregation (CQRS), and event sourcing resources.

### Contents

- [Libraries](#libraries)
- [Community resources](#community-resources)
- [Books](#books)
- [Articles](#articles)
- [Presentations](#presentations)
- [Example applications](#example-applications)

## Libraries

- [Chronik](https://hex.pm/packages/chronik) - A lightweight event sourcing micro framework for Elixir.

- [Commanded](https://github.com/slashdotdash/commanded) - Use Commanded to build your own Elixir applications following the CQRS/ES pattern. Provides support for command registration and dispatch, hosting and delegation to aggregate roots, event handling, and long running process managers.

    - [Commanded audit middleware](https://github.com/slashdotdash/commanded-audit-middleware) - Command auditing middleware for Commanded CQRS/ES applications using Ecto for persistence.

    - [Commanded Ecto projections](https://github.com/slashdotdash/commanded-ecto-projections) - Read model projections for Commanded using Ecto.

- [Eidetic](https://github.com/GT8Online/eidetic-elixir) - An event sourcing library for Elixir.

- [EventStore](https://github.com/slashdotdash/eventstore) - An Elixir event store using PostgreSQL for persistence.

    - [EventStore migrator](https://github.com/slashdotdash/eventstore-migrator) - Copy & transform event migration strategy for [EventStore](https://github.com/slashdotdash/eventstore).

- [Extreme](https://github.com/exponentially/extreme) - Elixir adapter for Greg Young's [Event Store](https://geteventstore.com/).

- [Perhap](https://github.com/Perhap/perhap) - Purely functional event store and service framework inspired by domain driven design and reactive architectures.

## Community resources

- [DDD/CQRS/ES Slack](https://ddd-cqrs-es.slack.com) - A Slack team for those who want to chat about domain-driven design, CQRS, event Sourcing, and sometimes random things. Main channel is language and framework agnostic.

- [Elixir lang Slack](https://elixir-lang.slack.com/) - This offical Elixir language Slack team includes an [#eventsourcing](https://elixir-lang.slack.com/messages/C2REECQ1Z/) channel for CQRS/ES and Elixir discussion.

## Books

- [Building Conduit](https://leanpub.com/buildingconduit) - Applying CQRS/ES to an Elixir and Phoenix web app.

## Articles

- [A Functional Foundation for CQRS/ES](http://verraes.net/2014/05/functional-foundation-for-cqrs-event-sourcing/) by [Mathias Verraes](https://twitter.com/mathiasverraes) - A CQRS architecture can be seen as a set of referentially transparent functions that model decisions and interpretation.

- [Building a CQRS/ES web application in Elixir using Phoenix](https://10consulting.com/2017/01/04/building-a-cqrs-web-application-in-elixir-using-phoenix/) by [Ben Smith](https://twitter.com/slashdotdash) - Case study describing how a web application was built using CQRS/ES.

- [CQRS with Elixir and Phoenix](http://jfcloutier.github.io/jekyll/update/2015/11/04/cqrs_elixir_phoenix.html) by Jean-François Cloutier - Implementing the CQRS pattern in Elixir.

- [DDD within Elixir/Phoenix project: Umbrella apps & Service Object](https://medium.com/@andreichernykh/thoughts-on-structuring-an-elixir-phoenix-project-cb083a8894ef) by [David McLeod](http://davidmcleod.com/).

- [Elixir: Domain driven design with Actor Model](https://www.linkedin.com/pulse/domain-driven-design-elixir-naveen-negi) by [Naveen Negi](https://www.linkedin.com/in/nav301186/).

- [Event Sourcing in Elixir](https://tech.zilverline.com/2017/04/07/elixir_event_sourcing) by Derek Kraan - Explore how we can use some of Elixir’s more interesting features to implement event sourcing.

## Presentations

- [Building CQRS/ES web applications in Elixir using Phoenix](https://10consulting.com/2017/03/23/building-cqrs-web-applications-in-elixir/) by [Ben Smith](https://twitter.com/slashdotdash).

- [CQRS with Erlang](https://vimeo.com/97318824) by [Bryan Hunter](https://twitter.com/bryan_hunter) @ NDC 2014 - Dive into CQRS, and explore a sample implementation written in Erlang. [ [slides](https://github.com/bryanhunter/cqrs-with-erlang/raw/ndc-oslo/cqrs-with-erlang.pptx) | [repo](https://github.com/bryanhunter/cqrs-with-erlang/tree/ndc-oslo) ]

- [Event Sourcing with Commanded](https://bitbucket.org/drozdyuk/bank-commanded-presentation-sep-25-2017) by [Andriy Drozdyuk](https://twitter.com/andriyko). [ [slides](https://bitbucket.org/drozdyuk/bank-commanded-presentation-sep-25-2017/raw/2398395ef908696c580800be37a0cdbb1a7d60be/presentation/Eventsourcing%20with%20Commanded.pdf) (PDF) | [repo](https://bitbucket.org/drozdyuk/bank-commanded-presentation-sep-25-2017) ]

- [Implementing CQRS on top of OTP (in Elixir)](http://slides.com/hubertlepicki/implementing-cqrs-in-elixir) by Hubert Łępicki.

- [Intro to Event Sourcing and CQRS](https://drteeth.github.io/elixir-es-cqrs/) in Elixir by [Ben Moss](https://twitter.com/benjamintmoss).

- [Perhap: Applying Domain Driven Design and Reactive Architectures to Functional Programming](https://www.youtube.com/watch?v=kq4qTk18N-c) at ElixirConf 2017 by [Rob Martin](https://twitter.com/version2beta).

## Example applications

- [Conduit](https://github.com/slashdotdash/conduit) - A blogging platform, an exemplary Medium.com clone, built as a Phoenix web application.

- [DDD Shipping Example](https://github.com/pcmarks/ddd_elixir_stage1_umbrella) by [Peter C Marks](https://github.com/pcmarks) - Elixir implementation of the shipping example from Eric Evan's "Domain-driven Design: Tackling Complexity in the Heart of Software" book.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Ben Smith](mailto:ben@10consulting.com) has waived all copyright and related or neighbouring rights to this work.
