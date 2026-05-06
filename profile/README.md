# Zizq Labs

Zizq Labs provides the [Zizq](https://zizq.io) job queue — a simple, zero
dependency, single binary job queue system that is both fast and durable.

Jobs can be enqueued and processed across a number of programming languages,
with a simple HTTP/2 and HTTP/1.1 API under the hood. Unlike other queue
systems, Zizq provides its own durable storage and does not require arbitrary
deadlines on features like job uniqueness.

## Features

* Works in any stack
* Arbitrary named queues
* HTTP/2 and HTTP/1.1 with support for JSON and MessagePack
* Granular job priorities
* Scheduled jobs
* Configurable backoff policies
* Configurable job retention policies
* Job introspection and management APIs
* Unique jobs
* Cron scheduling (recurring jobs)
* Built-in interactive terminal UI (`zizq top`)

## Resources

* [zizq.io website](https://zizq.io)
* [Getting Started Docs](https://zizq.io/docs/getting-started/)
* [Zizq Command Reference](https://zizq.io/docs/cli/)
* [Official Client Libraries](https://zizq.io/docs/clients)
* [Zizq Source](https://github.com/zizq-labs/zizq)

## Official Client Library Repositories

* [Official Ruby Client](https://github.com/zizq-labs/zizq-ruby)
* [Official Node.js Client](https://github.com/zizq-labs/zizq-node)

## Support & Feedback

If you need help using Zizq,
[create an issue](https://github.com/zizq-labs/zizq/issues) on the
[Zizq](https://github.com/zizq-labs/zizq) repo. Feedback is very welcome.
