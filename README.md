# Awesome Elixir and CQRS [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome Elixir, Command Query Responsibility Segregation (CQRS), and event sourcing resources.

### Contents

- [Libraries](#libraries)
- [Community resources](#community-resources)
- [Books](#books)
- [Articles](#articles)
- [Presentations](#presentations)
- [Screencasts](#screencasts)
- [Example applications](#example-applications)

## Libraries

- [Chronik](https://hex.pm/packages/chronik) - A lightweight event sourcing micro framework for Elixir.

- [Commanded](https://github.com/commanded/commanded) - Use Commanded to build your own Elixir applications following the CQRS/ES pattern. Provides support for command registration and dispatch, hosting and delegation to aggregate roots, event handling, and long running process managers.

    - [Commanded audit middleware](https://github.com/commanded/commanded-audit-middleware) - Command auditing middleware for Commanded CQRS/ES applications using Ecto for persistence.

    - [Commanded Ecto projections](https://github.com/commanded/commanded-ecto-projections) - Read model projections for Commanded using Ecto.

    - [Commanded scheduler](https://github.com/commanded/commanded-scheduler) - Schedule one-off and recurring commands for Commanded CQRS/ES applications .

    - [Commanded Swarm registry](https://github.com/commanded/commanded-swarm-registry) - Distributed process registry using Swarm for Commanded.

- [Eidetic](https://github.com/GT8Online/eidetic-elixir) - An event sourcing library for Elixir.

- [EventBus](https://github.com/otobus/event_bus) - Traceable, extendable and minimalist event bus implementation for Elixir with built-in event store and event watcher based on ETS.

- [EventStore](https://github.com/commanded/eventstore) - An Elixir event store using PostgreSQL for persistence.

- [Extreme](https://github.com/exponentially/extreme) - Elixir adapter for Greg Young's [Event Store](https://geteventstore.com/).

- [Maestro](https://github.com/toniqsystems/maestro) - An Elixir event store + CQRS library.

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

- [My First Event Sourced Application](https://www.codementor.io/leifio/my-first-event-sourced-application-flj7z32hl) by [Leif Gensert](https://twitter.com/leifg) - Building an event sourced application using [Commanded](https://github.com/commanded/commanded).

## Presentations

- [Building CQRS/ES web applications in Elixir using Phoenix](https://10consulting.com/2017/03/23/building-cqrs-web-applications-in-elixir/) by [Ben Smith](https://twitter.com/slashdotdash).

- [CQRS and Event Sourcing](https://www.youtube.com/watch?v=S3f6sAXa3-c) by [Bernardo Amorim](https://github.com/bamorim) @ Code Beam SF 2018 - A look into what Event Sourcing and Command Query Responsibility Segregation are and how they fit together, followed by a tutorial on how to implement an application using these concepts with Commanded (a framework for Elixir).

- [CQRS with Erlang](https://vimeo.com/97318824) by [Bryan Hunter](https://twitter.com/bryan_hunter) @ NDC 2014 - Dive into CQRS, and explore a sample implementation written in Erlang. [ [slides](https://github.com/bryanhunter/cqrs-with-erlang/raw/ndc-oslo/cqrs-with-erlang.pptx) | [repo](https://github.com/bryanhunter/cqrs-with-erlang/tree/ndc-oslo) ]

- [Event Sourcing with Commanded](https://bitbucket.org/drozdyuk/bank-commanded-presentation-sep-25-2017) by [Andriy Drozdyuk](https://twitter.com/andriyko). [ [slides](https://bitbucket.org/drozdyuk/bank-commanded-presentation-sep-25-2017/raw/2398395ef908696c580800be37a0cdbb1a7d60be/presentation/Eventsourcing%20with%20Commanded.pdf) | [repo](https://bitbucket.org/drozdyuk/bank-commanded-presentation-sep-25-2017) ]

- [Implementing CQRS on top of OTP (in Elixir)](http://slides.com/hubertlepicki/implementing-cqrs-in-elixir) by Hubert Łępicki. [ [video](https://www.youtube.com/watch?v=0StE5LzYxGQ) ]

- [Intro to Event Sourcing and CQRS](https://drteeth.github.io/elixir-es-cqrs/) in Elixir by [Ben Moss](https://twitter.com/benjamintmoss).

- [Perhap: Applying Domain Driven Design and Reactive Architectures to Functional Programming](https://www.youtube.com/watch?v=kq4qTk18N-c) at ElixirConf 2017 by [Rob Martin](https://twitter.com/version2beta).

- [Winter is coming](https://www.youtube.com/watch?v=vXTrLYAzOd0) by [Luis Ferreira](https://twitter.com/zamith) @ Functional Conf 2017 - Building maintainable applications by applying domain-driven design in Elixir using umbrella apps and its actor model. [ [slides](https://speakerdeck.com/zamith/winter-is-coming) | [video](https://www.youtube.com/watch?v=vXTrLYAzOd0) ]

## Screencasts

- [Building a single event sourced feature in Elixir using Commanded](https://www.youtube.com/watch?v=n7v73Rbk670) by [Shawn McCool](https://twitter.com/ShawnMcCool).

## Example applications

- [Bank](https://github.com/bamorim/commanded-bank) by [Bernardo Amorim](https://github.com/bamorim) - Sample Application for Elixir Brasil Talk.

- [Coins](https://github.com/bamorim/ex-cbsf2018) by [Bernardo Amorim](https://github.com/bamorim) - An example app using CQRS and Event Sourcing built with Commanded for a talk at CodeBEAM SF 2018.

- [Conduit](https://github.com/slashdotdash/conduit) - A blogging platform, an exemplary Medium.com clone, built as a Phoenix web application.

- [DDD Shipping Example](https://github.com/pcmarks/ddd_elixir_demo_stage1) by [Peter C Marks](https://github.com/pcmarks) - Elixir implementation of the shipping example from Eric Evan's "Domain-driven Design: Tackling Complexity in the Heart of Software" book.

- [Simple Pay](https://github.com/ChrisYammine/simple_pay) by [Christopher Yammine](https://github.com/ChrisYammine) - An exploration of using CQRS/ES with Elixir & EventStore database.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Ben Smith](mailto:ben@10consulting.com) has waived all copyright and related or neighbouring rights to this work.
