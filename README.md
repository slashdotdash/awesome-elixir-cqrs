# Awesome Elixir and CQRS [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome Elixir, Command Query Responsibility Segregation (CQRS), and event sourcing resources.

### Contents

- [Libraries](#libraries)
- [Community resources](#community-resources)
- [Books](#books)
- [Articles](#articles)
- [Presentations](#presentations)
- [Research papers](#research-papers)
- [Screencasts](#screencasts)
- [Example applications](#example-applications)

## Libraries

- [Chronik](https://hex.pm/packages/chronik) - A lightweight event sourcing micro framework for Elixir.

- [Commanded](https://github.com/commanded/commanded) - Use Commanded to build your own Elixir applications following the CQRS/ES pattern. Provides support for command registration and dispatch, hosting and delegation to aggregate roots, event handling, and long running process managers.

    - [Commanded audit middleware](https://github.com/commanded/commanded-audit-middleware) - Command auditing middleware for Commanded CQRS/ES applications using Ecto for persistence.

    - [Commanded Ecto projections](https://github.com/commanded/commanded-ecto-projections) - Read model projections for Commanded using Ecto.

    - [Commanded scheduler](https://github.com/commanded/commanded-scheduler) - Schedule one-off and recurring commands for Commanded CQRS/ES applications .

    - [Commanded Swarm registry](https://github.com/commanded/commanded-swarm-registry) - Distributed process registry using Swarm for Commanded.

- [Disco](https://github.com/andreapavoni/disco) - Simple, opinionated yet flexible library to build CQRS/ES driven systems.

- [Eidetic](https://github.com/rawkode/eidetic-elixir) - An event sourcing library for Elixir.

- [ES](https://github.com/nerdyworm/es) - Event Sourcing for Ecto and Postgresl/Dynamodb events storage.

- [EventBus](https://github.com/otobus/event_bus) - Traceable, extendable and minimalist event bus implementation for Elixir with built-in event store and event watcher based on ETS.

- [Eventlog](https://github.com/nerdyworm/eventlog) - A simple event log backed by dynamodb and dynamodb streams.

- [EventStore](https://github.com/commanded/eventstore) - An Elixir event store using PostgreSQL for persistence.

- [Extreme](https://github.com/exponentially/extreme) - Elixir adapter for Greg Young's [Event Store](https://geteventstore.com/).

- [Fable](https://github.com/CargoSense/fable) - An Elixir event sourcing library.

- [Helios.Aggregate](https://github.com/exponentially/helios_aggregate) - Elixir library defining Aggregate behaviour and providing extendable facility for aggregate command pipeline.

- [Incident](https://github.com/pedroassumpcao/incident) - Event Sourcing and CQRS in Elixir abstractions.

- [Maestro](https://github.com/toniqsystems/maestro) - An Elixir event store + CQRS library.

- [Pachyderm](https://github.com/CrowdHailer/pachyderm) - A virtual/immortal/durable/resilient/global actor "always exists" and "never fails".

- [Perhap](https://github.com/Perhap/perhap) - Purely functional event store and service framework inspired by domain driven design and reactive architectures.

- [Seven Otters](https://github.com/sevenotters/sevenotters) - A CQRS/ES Starter Kit for the BEAM.

- [TeaVent](https://github.com/Qqwy/elixir-tea_vent) - TeaVent allows you to perform event-dispatching in a style that is a mixture of Event Sourcing and The "Elm Architecture" (TEA).

## Community resources

- [Awesome Domain-Driven Design](https://github.com/heynickc/awesome-ddd) - A (non language specific) curated list of Domain-Driven Design (DDD), Command Query Responsibility Segregation (CQRS), Event Sourcing, and Event Storming resources.

- [DDD/CQRS/ES Slack](https://ddd-cqrs-es.slack.com) - A Slack team for those who want to chat about domain-driven design, CQRS, event Sourcing, and sometimes random things. Main channel is language and framework agnostic. [Join **ddd-cqrs-es** on Slack](https://j.mp/ddd-es-cqrs) to get an invite.

- [Elixir lang Slack](https://elixir-lang.slack.com/) - This offical Elixir language Slack team includes an [#eventsourcing](https://elixir-lang.slack.com/messages/C2REECQ1Z/) channel for CQRS/ES and Elixir discussion. [Join **Elixir** on Slack](https://elixir-slackin.herokuapp.com/) to get an invite.

## Books

- [Building Conduit](https://leanpub.com/buildingconduit) - Applying CQRS/ES to an Elixir and Phoenix web app.

## Articles

- [A Functional Foundation for CQRS/ES](http://verraes.net/2014/05/functional-foundation-for-cqrs-event-sourcing/) by [Mathias Verraes](https://twitter.com/mathiasverraes) - A CQRS architecture can be seen as a set of referentially transparent functions that model decisions and interpretation.

- [Building a CQRS/ES web application in Elixir using Phoenix](https://10consulting.com/2017/01/04/building-a-cqrs-web-application-in-elixir-using-phoenix/) by [Ben Smith](https://twitter.com/slashdotdash) - Case study describing how a web application was built using CQRS/ES.

- [CQRS with Elixir and Phoenix](http://jfcloutier.github.io/jekyll/update/2015/11/04/cqrs_elixir_phoenix.html) by Jean-François Cloutier - Implementing the CQRS pattern in Elixir.

- [DDD within Elixir/Phoenix project: Umbrella apps & Service Object](https://medium.com/@andreichernykh/thoughts-on-structuring-an-elixir-phoenix-project-cb083a8894ef) by [David McLeod](http://davidmcleod.com/).

- [Elixir: Domain driven design with Actor Model](https://www.linkedin.com/pulse/domain-driven-design-elixir-naveen-negi) by [Naveen Negi](https://www.linkedin.com/in/nav301186/).

- [Event Sourcing in Elixir](https://tech.zilverline.com/2017/04/07/elixir_event_sourcing) by Derek Kraan - Explore how we can use some of Elixir’s more interesting features to implement event sourcing.

- [Event Sourcing in React, Redux & Elixir](https://medium.com/rapport-blog/event-sourcing-in-react-redux-elixir-how-we-write-fast-scalable-real-time-apps-at-rapport-4a26c3aa7529) by [Gary McAdam](https://twitter.com/gpmcadam) - How we write fast, scalable, real-time apps at Rapport.

- [My First Event Sourced Application](https://www.codementor.io/leifio/my-first-event-sourced-application-flj7z32hl) by [Leif Gensert](https://twitter.com/leifg) - Building an event sourced application using [Commanded](https://github.com/commanded/commanded).

### 2019

- [Event Sourcing With Elixir](https://blog.nootch.net/post/event-sourcing-with-elixir/) by [Bruno Antunes](https://twitter.com/b_antunes) - A multi-part blog series on event sourcing with Elixir using Commanded.

- [My Journey into CQRS and Event Sourcing](https://medium.com/@rodrigo.botti/my-journey-into-cqrs-and-event-sourcing-4bd7d0c1c670) by [Rodrigo Botti](https://github.com/rodrigobotti) - Learning these patterns by building a patient consent example application in Elixir.

- [Creating a single-node Elixir/Phoenix web app with Commanded & Postgres](https://bitfield.co/commanded-part1/) by [Ben Moss](https://github.com/drteeth) - A blog post series to walk the reader through installing and configuring Commanded for use in a single-node Phoenix web app backed by Postgres.

### 2021

- [Building an event-sourced game with Phoenix Liveview](https://blog.chorip.am/articles/phoenix-liveview-event-sourced-game-intro) by [Charles Desneuf](https://twitter.com/SelrahcD) - A series on building an event-sourced game in Elixir with Phoenix Liveview.

- [Getting started with Elixir and EventStoreDB with the Spear gRPC client](https://www.eventstore.com/blog/getting-started-with-elixir-and-eventstoredb-with-the-spear-grpc-client) by Michael Davis.

## Presentations

### 2014

- [CQRS with Erlang](https://vimeo.com/97318824) by [Bryan Hunter](https://twitter.com/bryan_hunter) @ NDC 2014 - Dive into CQRS, and explore a sample implementation written in Erlang. [ [slides](https://github.com/bryanhunter/cqrs-with-erlang/raw/ndc-oslo/cqrs-with-erlang.pptx) | [source code](https://github.com/bryanhunter/cqrs-with-erlang/tree/ndc-oslo) ]

### 2016

- [Implementing CQRS on top of OTP (in Elixir)](http://slides.com/hubertlepicki/implementing-cqrs-in-elixir) by Hubert Łępicki. [ [video](https://www.youtube.com/watch?v=0StE5LzYxGQ) ]

### 2017

- [Building CQRS/ES web applications in Elixir using Phoenix](https://10consulting.com/2017/03/23/building-cqrs-web-applications-in-elixir/) by [Ben Smith](https://twitter.com/slashdotdash).

- [Event Sourcing with Commanded](https://bitbucket.org/drozdyuk/bank-commanded-presentation-sep-25-2017) by [Andriy Drozdyuk](https://twitter.com/andriyko). [ [slides](https://bitbucket.org/drozdyuk/bank-commanded-presentation-sep-25-2017/raw/2398395ef908696c580800be37a0cdbb1a7d60be/presentation/Eventsourcing%20with%20Commanded.pdf) | [source code](https://bitbucket.org/drozdyuk/bank-commanded-presentation-sep-25-2017) ]

- [Intro to Event Sourcing and CQRS](https://drteeth.github.io/elixir-es-cqrs/) in Elixir by [Ben Moss](https://twitter.com/benjamintmoss).

- [Perhap: Applying Domain Driven Design and Reactive Architectures to Functional Programming](https://www.youtube.com/watch?v=kq4qTk18N-c) at ElixirConf 2017 by [Rob Martin](https://twitter.com/version2beta).

- [Winter is coming](https://www.youtube.com/watch?v=vXTrLYAzOd0) by [Luis Ferreira](https://twitter.com/zamith) @ Functional Conf 2017 - Building maintainable applications by applying domain-driven design in Elixir using umbrella apps and its actor model. [ [slides](https://speakerdeck.com/zamith/winter-is-coming) | [video](https://www.youtube.com/watch?v=vXTrLYAzOd0) ]

### 2018

- [Building beautiful systems with Phoenix contexts](https://www.youtube.com/watch?v=l3VgbSgo71E) by [Andrew Hao](https://github.com/andrewhao) @ ElixirDaze 2018 - Learn about Phoenix contexts from their origins in domain-driven design and how they help you to organise an Elixir application by providing rules around communication, boundary enforcement and testing. [ [slides](https://speakerdeck.com/andrewhao/building-beautiful-systems-with-phoenix-contexts-and-ddd) ]

- [CQRS and Event Sourcing](https://www.youtube.com/watch?v=S3f6sAXa3-c) by [Bernardo Amorim](https://github.com/bamorim) @ Code Beam SF 2018 - A look into what Event Sourcing and Command Query Responsibility Segregation are and how they fit together, followed by a tutorial on how to implement an application using these concepts with Commanded (a framework for Elixir).

- [Event-driven architectures in Elixir](https://www.youtube.com/watch?v=8qDXG7tnl9w) by [Maciej Kaszubowski](https://github.com/mkaszubowski) @ ElixirConf EU 2018 - Learn how you can improve your architecture and reduce coupling by using events. [ [slides](http://s3.amazonaws.com/erlang-conferences-production/media/files/000/000/875/original/Maciej_Kaszubowski_-_Event-driven_architectures_in_Elixir.pdf) ]

- [Event Sourcing in Elixir](https://www.youtube.com/watch?v=1lOUtisllFA) by [Pedro Assumpção](https://twitter.com/pedroassumpcao) @ ChicagoElixir Meetup, November 2018 - In this talk, Pedro quickly introduces Event Sourcing and CQRS, but the main part is about [FootBroker](https://footbroker.tk), an online soccer fantasy game that it is running in production in a beta stage, and has its main pieces using Event Sourcing and CQRS patterns.

- [Event Sourcing in Real World Applications Challenges, Successes and Lessons Learned](https://www.youtube.com/watch?v=ESRjkG5f7wg) by [James Smith](https://twitter.com/st23am) @ ElixirConf 2018 - Building a real time auction application for supplying fuel to ships using event sourcing.

### 2019

- [An event-driven approach to building Elixir applications](https://www.youtube.com/watch?v=TdGxvekg6xM) by [Ben Smith](https://twitter.com/slashdotdash) @ Code Elixir LDN 2019 - We experience the real world by reacting to events that have occurred, what if we modelled our Elixir applications in the same way? [ [slides](https://10consulting.com/2019/07/18/event-driven-elixir-applications/) ]

- [Building Event Sourced Apps](https://speakerdeck.com/leifg/building-event-sourced-apps) by [Leif Gensert](https://twitter.com/leifg) @ London BEAM User Group, January 2019 - Instead of defining a global data model that fits all of your use cases think about the things your system does. Record the events that occur and then build multiple data models that fit your individual use cases.

- [CQRS/ES & Elixir](https://github.com/bdubaut/talks/tree/master/2019/Elixir/CQRS_ES_and_Elixir) by [Bertrand Dubaut](https://github.com/bdubaut) @ Amsterdam Elixir Meetup, September 2019 - An introduction to the CQRS/ES architecture pattern and how to implement it in your application in Elixir with the Commanded framework.

- [Elixir + CQRS - Architecting for Availability, Operability, and Maintainability At PagerDuty](https://www.youtube.com/watch?v=-d2NPc8cEnw) by [Jon Grieman](https://github.com/jongrieman) @ ElixirConf 2019 - This talk looks at the service that powers PagerDuty’s timeline entries, a critical component for understanding what happens during an incident and covers how the service is architected for Command Query Responsibility Segregation and the benefits of those choices.

- [Event sourcing in practice - Using Elixir to build event-driven applications](https://10consulting.com/2019/03/29/event-sourcing-in-practice/) by [Ben Smith](https://twitter.com/slashdotdash) @ Elixir London user group, March 2019 - Practical example of event sourcing in Elixir.

- [Event sourcing/CQRS in Elixir with Commanded: Where the rubber hits the road](https://drteeth.github.io/attend-elixir-talk/) by [Ben Moss](https://twitter.com/benjamintmoss) @ Toronto Elixir meetup, May 2019. [ [source code](https://github.com/drteeth/attend) ]

- [gen_persistence: persist the state of your processes](https://www.youtube.com/watch?v=g-2qYXMexg8) by [Benoît Chesneau](https://twitter.com/benoitc) @ Code BEAM STO 2019 - This talk describes the usage of `gen_persistence` and how to create custom plugins to store events and snapshots. [ [slides](https://codesync.global/uploads/media/activity_slides/0001/02/66d3ad28168e01c69a8887fe5fc21364396d28bc.pdf) ]

### 2020

- [Event Sourcing with Elixir](https://github.com/PJUllrich/event-sourcing-with-elixir) by [Peter Ullrich](https://twitter.com/PJUllrich) @ ElixirConf EU 2020 - Introduction to event sourcing with examples using EventStore. [ [slides](https://raw.githubusercontent.com/PJUllrich/event-sourcing-with-elixir/master/slides.pdf) ]

## Research papers

### 2017

- [The Dark Side of Event Sourcing: Managing Data Conversion](https://www.movereem.nl/files/2017SANER-eventsourcing.pdf) by Michiel Overeem, Marten Spoor, and Slinger Jansen.

### 2021

- [An Empirical Characterization of Event Sourced Systems and Their Schema Evolution - Lessons from Industry](https://arxiv.org/abs/2104.01146) by Michiel Overeem, Marten Spoor, Slinger Jansen, Sjaak Brinkkemper.

## Screencasts

- [Building a single event sourced feature in Elixir using Commanded](https://www.youtube.com/watch?v=n7v73Rbk670) by [Shawn McCool](https://twitter.com/ShawnMcCool).

## Example applications

- [Bank](https://github.com/bamorim/commanded-bank) by [Bernardo Amorim](https://github.com/bamorim) - Sample Application for Elixir Brasil Talk.

- [Bonfire](https://github.com/qhwa/bonfire) by [Qiu Hua](https://github.com/qhwa) - A small project for exploring some interesting approaches to a delightful web application.

- [Coins](https://github.com/bamorim/ex-cbsf2018) by [Bernardo Amorim](https://github.com/bamorim) - An example app using CQRS and Event Sourcing built with Commanded for a talk at CodeBEAM SF 2018.

- [Conduit](https://github.com/slashdotdash/conduit) - A blogging platform, an exemplary Medium.com clone, built as a Phoenix web application.

- [DDD Shipping Example](https://github.com/pcmarks/ddd_elixir_demo_stage1) by [Peter C Marks](https://github.com/pcmarks) - Elixir implementation of the shipping example from Eric Evan's "Domain-driven Design: Tackling Complexity in the Heart of Software" book.

- [Gift card demo](https://github.com/slashdotdash/gift-card-demo/) by [Ben Smith](https://twitter.com/slashdotdash) - a Commanded demo application focused around a simplified gift card domain using Phoenix LiveView for realtime UI updates.

- [Segment Challenge](https://github.com/slashdotdash/segment-challenge/) by [Ben Smith](https://twitter.com/slashdotdash) - a full featured Elixir Phoenix web application built with Commanded used to host Strava competitions for athletes.

- [Simple Pay](https://github.com/ChrisYammine/simple_pay) by [Christopher Yammine](https://github.com/ChrisYammine) - An exploration of using CQRS/ES with Elixir & EventStore database.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Ben Smith](mailto:ben@10consulting.com) has waived all copyright and related or neighbouring rights to this work.
