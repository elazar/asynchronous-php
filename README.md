# Asynchronous PHP

Over time, I've noticed a lot of interesting information, code, and people centered around topics related to asynchronous programming using PHP. I thought it might be useful to try to catalog them all in one place. This repository is the result and fairly experimental in concept. Feel free to [file an issue](https://github.com/elazar/asynchronous-php/issues) or [submit a pull request](https://help.github.com/articles/creating-a-pull-request/) if you think there's anything that should be added or changed.

* [Concepts](#concepts)
  * [Asynchronous](#asynchronous)
  * [Blocking](#blocking)
  * [Concurrency](#concurrency)
  * [Coroutines](#coroutines)
  * [Events](#events)
  * [Multitasking](#multitasking)
  * [Observables](#observables)
  * [Promises](#promises)
  * [Reactive Programming](#reaction-programming)
  * [Threads](#threads)
* [Projects](#projects)
  * [amphp](#amphp)
  * [Async PHP](#async-php)
  * [Icicle](#icicle)
  * [React](#react)
  * [Recoil](#recoil)
  * [Swoole](#swoole)
* [Repositories](#repositories)
  * [Asynchronous](#asynchronous-1)
  * [Caching](#caching)
  * [CLI](#cli)
  * [Compression](#compression)
  * [Databases](#databases)
  * [DNS](#dns)
  * [Events](#events)
  * [Filesystems](#filesystems)
  * [GUIs](#guis)
  * [HTTP](#http)
  * [Interoperability](#interoperability)
  * [IRC](#irc)
  * [Messaging](#messaging)
  * [Multitasking](#multitasking)
  * [Networking](#networking)
  * [Promises](#promises)
  * [Sockets and Streams](#sockets-and-streams)
  * [Web Applications](#web-applications)
  * [Web Services](#web-services)
* [People](#people)

## Concepts

### Asynchronous

* [Asynchronous I/O - Wikipedia](https://en.wikipedia.org/wiki/Asynchronous_I/O)
* [Async PHP](https://speakerdeck.com/chrispitt/async-php-1) by Christopher Pitt / assertchris

### Blocking

* [Blocking (computing) - Wikipedia](https://en.wikipedia.org/wiki/Blocking_(computing))

### Concurrency

* [Concurrency (computer science) - Wikipedia](https://en.wikipedia.org/wiki/Concurrency_(computer_science))

### Coroutines

* [Cooperative multitasking with generators](https://speakerdeck.com/chrispitt/cooperative-multitasking-with-generators) by Christopher Pitt / assertchris
* [Cooperative multitasking using coroutines (in PHP!)](https://nikic.github.io/2012/12/22/Cooperative-multitasking-using-coroutines-in-PHP.html) by Nikita Popov / nikic
* [Coroutine - Wikipedia](https://en.wikipedia.org/wiki/Coroutine)

### Events

* [Event (computing) - Wikipedia](https://en.wikipedia.org/wiki/Event_(computing))
* [Event-driven programming - Wikipedia](https://en.wikipedia.org/wiki/Event-driven_programming)
* [Event loop - Wikipedia](https://en.wikipedia.org/wiki/Event_loop)

### Multitasking

* [Computer multitasking - Wikipedia](https://en.wikipedia.org/wiki/Computer_multitasking#Cooperative_multitasking)

### Observables

* [ReactiveX - Observable](http://reactivex.io/documentation/observable.html)
* [RxJS Observables vs Promises](https://egghead.io/lessons/rxjs-rxjs-observables-vs-promises)

### Promises

* [Futures and promises - Wikipedia](https://en.wikipedia.org/wiki/Futures_and_promises)
* [Promises and Generators](https://github.com/evert/promises-and-generators) by Evert Pot / evert

### Reactive Programming

* [Reactive programming - Wikipedia](https://en.wikipedia.org/wiki/Reactive_programming)
* [The introduction to Reactive Programming you've been missing](https://gist.github.com/staltz/868e7e9bc2a7b8c1f754) by André Staltz / staltz

### Threads

* [Thread (computing) - Wikipedia](https://en.wikipedia.org/wiki/Thread_(computing))
* [Thread carefully](http://blog.madewithlove.be/post/thread-carefully/) by Maxime Fabre

## Projects

### amphp

A non-blocking concurrency framework for PHP applications.

- GitHub: [amphp](https://github.com/amphp)
- Website: [amphp.org](http://amphp.org)
- [amphp blog series](http://blog.kelunik.com/tags/amphp.html) by Niklas Keller / kelunik

### Async PHP

- GitHub: [asyncphp](https://github.com/asyncphp)

### Icicle

Icicle is a PHP library for writing asynchronous code using synchronous coding techniques.

- Github: [icicleio](https://github.com/icicleio)
- Website: [icicle.io](http://icicle.io)

### React

Event-driven, non-blocking I/O with PHP.

- GitHub: [reactphp](https://github.com/reactphp)
- Website: [reactphp.org](http://reactphp.org/)
- [React series](http://blog.wyrihaximus.net/categories/reactphp/) by Cees-Jan Kiewiet / wyrihaximus

### Recoil

Cooperative multitasking for PHP via coroutines.

- GitHub: [recoilphp](https://github.com/recoilphp)
- Website: [recoil.io](http://recoil.io)

### Swoole

Asynchronous concurrent distributed networking framework for PHP

- GitHub: [swoole](https://github.com/swoole)
- Website: [swoole.com](http://www.swoole.com)

## Repositories

### Asynchronous

* [asm89/Rx.PHP](https://github.com/asm89/Rx.PHP) - Libraries to compose asynchronous and event-based programs using observable collections and LINQ-style query operators
* [clue/php-block-react](https://github.com/clue/php-block-react) - Lightweight library that eases integrating async components built for [React](#react) in a traditional blocking environment
* [icicleio/icicle](https://github.com/icicleio/icicle) - Library for writing asynchronous code using synchronous coding techniques

### Caching

* [amphp/cache](https://github.com/amphp/cache) - A promise-aware caching API built on [amp](#amphp)
* [amphp/redis](https://github.com/amphp/redis) - An async redis client built on [amp](#amphp)
* [asyncphp/icicle-cache](https://github.com/asyncphp/icicle-cache) - A simple cache library, built for [Icicle](#icicle), with anti-stampede and promises
* [clue/php-redis-react](https://github.com/clue/php-redis-react) - Async Redis client implementation built on [React](#react)
* [clue/php-redis-server](https://github.com/clue/php-redis-server) - A redis server implementation in pure PHP
* [nrk/predis-async](https://github.com/nrk/predis-async) - Asynchronous Redis client library built on [React](#react)
* [reactphp/cache](https://github.com/reactphp/cache) - [React](#react) async caching
* [swoole/redis-async](https://github.com/swoole/redis-async) - Asynchronous Redis client for PHP with built-in connection pooling

### CLI

* [clue/php-bitbake-react](https://github.com/clue/php-bitbake-react) - Programmatically control your bitbake build shell built on [React](#react)
* [clue/php-readline-react](https://github.com/clue/php-readline-react) - Experimental reactive binding for ext-readline, built on [React](#react)
* [clue/php-shell-react](https://github.com/clue/php-shell-react) - Run async commands within any interactive shell command built on [React](#react)
* [clue/php-stdio-react](https://github.com/clue/php-stdio-react) - Async event-driven and UTF-8 aware standard console input & output for [React](#react)

### Compression

* [clue/php-tar-react](https://github.com/clue/php-tar-react) - Async streaming parser for the TAR file format built on [React](#react)
* [clue/php-zlib-react](https://github.com/clue/php-zlib-react) - Streaming zlib compressor and decompressor built on [React](#react)

### Databases

* [amphp/mysql](https://github.com/amphp/mysql) - An async mysql client built on [amp](#amphp)
* [amphp/pgsql](https://github.com/amphp/pgsql) - A non-blocking PostgreSQL library built on [amp](#amphp)
* [recoilphp/database](https://github.com/recoilphp/database) - Asynchronous PDO for [Recoil](#recoil)
* [swoole/mysql-async](https://github.com/swoole/mysql-async) - Async MySQL client for PHP

### DNS

* [amphp/dns](https://github.com/amphp/dns) - Async DNS resolution built on [amp](#amphp)
* [clue/php-mdns-react](https://github.com/clue/php-mdns-react) - Simple async multicast DNS (mDNS) resolver built on [React](#react)
* [icicleio/dns](https://github.com/icicleio/dns) - Asynchronous DNS component for [Icicle](#icicle)
* [reactphp/dns](https://github.com/reactphp/dns) - Asynchronous DNS resolver

### Events

* [asyncphp/remit](https://github.com/asyncphp/remit) - Distributed event emitter
* [icicleio/event-emitter](https://github.com/icicleio/event-emitter) - Library that allows objects to emit events that invoke a set of registered callbacks
* [recoilphp/event-emitter](https://github.com/recoilphp/event-emitter) - A coroutine-based event emitter
* [reactphp/event-loop](https://github.com/reactphp/event-loop) - React's core reactor event-loop
* [sabre/event](http://sabre.io/event/) - Lightweight library for event-based development

### Filesystems

* [amphp/file](https://github.com/amphp/file) - An async filesystem library built on [amp](#amphp)
* [icicleio/filesystem](https://github.com/icicleio/filesystem) - Asynchronous file access for [Icicle](#icicle)
* [reactphp/filesystem](https://github.com/reactphp/filesystem) - Evented filesystem access
* [WyriHaximus/reactphp-filesystem-s3](https://github.com/WyriHaximus/reactphp-filesystem-s3) - AWS S3 adapter for [reactphp/filesystem](https://github.com/reactphp/filesystem)

### GUIs

* [clue/php-zenity-react](https://github.com/clue/php-zenity-react) - Build graphical desktop (GUI) applications in PHP

### HTTP

* [amphp/artax](https://github.com/amphp/artax) - An async HTTP/1.1 client built on [amp](#amphp)
* [clue/php-buzz-react](https://github.com/clue/php-buzz-react) - Simple async HTTP client for concurrently processing requests built on [React](#react)
* [icicleio/http](https://github.com/icicleio/http) - HTTP component for [Icicle](#icicle)
* [icicleio/psr7-bridge](https://github.com/icicleio/psr7-bridge) - PSR-7 Bridge for [Icicle](#icicle) HTTP component
* [reactphp/http](https://github.com/reactphp/http) - [React](#react) HTTP server
* [reactphp/http-client](https://github.com/reactphp/http-client) - Asynchronous HTTP client library
* [WyriHaximus/react-guzzle-psr7](https://github.com/WyriHaximus/react-guzzle-psr7) - [React](#react) HTTP client adapter for Guzzle 6
* [WyriHaximus/ReactGuzzleRing](https://github.com/WyriHaximus/ReactGuzzleRing) - [React](#react) HTTP client wrapper for Guzzle 5
* [WyriHaximus/ReactGuzzle](https://github.com/WyriHaximus/ReactGuzzle) - [React](#react) HTTP client wrapper for Guzzle 4

## Interoperability

* [icicleio/react-adapter](https://github.com/icicleio/react-adapter) - Adapts the event loop and promises of [Icicle](#icicle) to interfaces compatible with [React](#react)

### IRC

* [clue/php-quassel-react](https://github.com/clue/php-quassel-react) - Streaming event-driven access to your Quassel IRC core built on [React](#react)
* [phergie/phergie-irc-bot-react](https://github.com/phergie/phergie-irc-bot-react) - IRC bot built on [React](#react)

### Messaging

* [reactphp/stomp](https://github.com/reactphp/stomp) - STOMP bindings for [React](#react)
* [reactphp/zmq](https://github.com/reactphp/zmq) - ZeroMQ bindings for [React](#react)
* [recoilphp/amqp](https://github.com/recoilphp/amqp) - An asynchronous AMQP client for [React](#react) and [Recoil](#recoil)

### Multitasking

* [amphp/amp](https://github.com/amphp/amp) - A non-blocking concurrency framework for PHP applications
* [amphp/process](https://github.com/amphp/process) - An async process dispatcher built on [amp](#amphp)
* [amphp/thread](https://github.com/amphp/thread) - An async multi-threaded task dispatcher built on [amp](#amphp)
* [asyncphp/assistant](https://github.com/asyncphp/assistant) - A neat wrapper around multi-process abstractions and distributed event emitters
* [asyncphp/doorman](https://github.com/asyncphp/doorman) - Child process management
* [icicleio/concurrent](https://github.com/icicleio/concurrent) - Concurrency component for [Icicle](#icicle)
* [php-pm/php-pm](https://github.com/php-pm/php-pm) - CLI process manager for modern Request-Response PHP Applications - with a builtin load-balancer.
* [reactphp/child-process](https://github.com/reactphp/child-process) - Library for executing child processes
* [recoilphp/recoil](https://github.com/recoilphp/recoil) - Cooperative multitasking for PHP via coroutines
* [WyriHaximus/reactphp-child-process-messenger](https://github.com/WyriHaximus/reactphp-child-process-messenger) - Plain messages and RPC style STDIN/OUT/ERR wrapper around [react/child-process](https://github.com/reactphp/child-process)
* [WyriHaximus/reactphp-child-process-pool](https://github.com/WyriHaximus/reactphp-child-process-pool) - Pool implementation for [WyriHaximus/reactphp-child-process-messenger](https://github.com/WyriHaximus/reactphp-child-process-messenger)

### Networking

* [clue/php-ami-react](https://github.com/clue/php-ami-react) - Simple async event-driven access to the Asterisk Manager Interface (AMI) built on [React](#react)
* [clue/php-icmp-react](https://github.com/clue/php-icmp-react) - Simple async low-level ICMP (ping) messaging library built on [React](#react)
* [clue/php-multicast-react](https://github.com/clue/php-multicast-react) - Simple multicast UDP messages built on [React](#react)
* [clue/php-ssdp-react](https://github.com/clue/php-ssdp-react) - Async Simple Service Discovery Protocol (SSDP) built on [React](#react)
* [clue/php-solusvm-api-react](https://github.com/clue/php-solusvm-api-react) - Simple async access to your VPS box through the SolusVM API built on [React](#react)
* [clue/php-socks-react](https://github.com/clue/php-socks-react) - Async SOCKS TCP tunnel proxy client and server built on [React](#react)
* [clue/php-wake-on-lan-react](https://github.com/clue/php-wake-on-lan-react) - Turn on your PC with Wake-On-LAN requests via [React](#react)
* [reactphp/datagram](https://github.com/reactphp/datagram) - UDP client and server sockets for [React](#react)
* [reactphp/whois](https://github.com/reactphp/whois) - Whois client based on [React](#react)
* [umpirsky/wisdom](https://github.com/umpirsky/wisdom) - Domain availability checker
* [WyriHaximus/PhuninNode](https://github.com/WyriHaximus/PhuninNode) - munin-node port aiming to provide application monitoring utilizing munin

### Promises

* [guzzle/promises](https://github.com/guzzle/promises) - Promises/A+ library for PHP with synchronous support
* [reactphp/promise](https://github.com/reactphp/promise) - A lightweight implementation of CommonJS Promises/A for PHP
* [reactphp/promise-timer](https://github.com/reactphp/promise-timer) - Timeout implementation for the [React](#react) promises library

### Sockets and Streams

* [amphp/socket](https://github.com/amphp/socket) - Non-blocking socket and TLS functionality built on [amp](#amphp)
* [clue/php-socket-react](https://github.com/clue/php-socket-react) - Binding for raw sockets (ext-sockets) in [React](#react)
* [icicleio/socket](https://github.com/icicleio/socket) - Asynchronous stream socket server and client for [Icicle](#icicle)
* [icicleio/stream](https://github.com/icicleio/stream) - Coroutine-based asynchronous stream interfaces for [Icicle](#icicle)
* [reactphp/socket](https://github.com/reactphp/socket) - Asynchronous socket server
* [reactphp/socket-client](https://github.com/reactphp/socket-client) - Async connector to open TCP/IP and SSL/TLS based connections
* [reactphp/stream](https://github.com/reactphp/stream) - Asynchronous OO stream wrapper
* [WyriHaximus/reactphp-psr7-stream-converter](https://github.com/WyriHaximus/reactphp-psr7-stream-converter) - PSR-7 to [React](#react) stream converter and vice versa

### Web Applications

* [amphp/aerys](https://github.com/amphp/aerys) - A non-blocking HTTP application, WebSocket and file server
* [amphp/aerys-session](https://github.com/amphp/aerys-session) - Session management for Aerys server
* [bixuehujin/blink](https://github.com/bixuehujin/blink) - Microframework for building long-running high-performance services
* [clue/php-sse-react](https://github.com/clue/php-sse-react) - Streaming async HTML5 Server-Sent Events server built on [React](#react)
* [ratchetphp/Pawl](https://github.com/ratchetphp/Pawl) - Asynchronous WebSocket client
* [ratchetphp/Ratchet](https://github.com/ratchetphp/Ratchet) - Asynchronous WebSocket server
* [reactphp/espresso](https://github.com/reactphp/espresso) - Proof-of-concept microframework that integrates Silex with [React](#react)
* [swoole/swoole-src](https://github.com/swoole/swoole-src) - Event-based concurrent framework for internet applications in PHP, written in C
* [voryx/Thruway](https://github.com/voryx/Thruway) - client and router implementation of the Web Application Messaging Protocol built on [React](#react)

### Web Services

* [clue/php-packagist-api-react](https://github.com/clue/php-packagist-api-react) - Simple async access to packagist.org's API
* [clue/php-viewvc-api-react](https://github.com/clue/php-viewvc-api-react) - Simple async API-like access to your ViewVC web interface built on [React](#react)
* [clue/php-soap-react](https://github.com/clue/php-soap-react) - A simple async SOAP webservice client built on [React](#react)
* [bergie/dnode-php](https://github.com/bergie/dnode-php) - DNode RPC protocol implementation

## People

* Alexander / asm89 - [GitHub](https://github.com/asm89)
* Bob Weinand / bwoebi - [GitHub](https://github.com/bwoebi), [Twitter](https://twitter.com/bwoebi)
* Cees-Jan Kiewiet / wyrihaximus - [GitHub](https://github.com/wyrihaximus), [Twitter](https://twitter.com/wyrihaximus)
* Chris Boden / cboden - [GitHub](https://github.com/cboden), [Twitter](http://twitter.com/boden_c)
* Christian Lück / clue - [GitHub](https://github.com/clue), [Twitter](https://twitter.com/another_clue)
* Christopher Pitt / assertchris - [GitHub](https://github.com/assertchris), [Twitter](https://twitter.com/assertchris), [Twitch](http://www.twitch.tv/assertchris)
* Daniel Lowrey / rdlowrey - [GitHub](https://github.com/rdlowrey), [Twitter](https://twitter.com/rdlowrey)
* Niklas Keller / kelunik - [GitHub](https://github.com/kelunik), [Twitter](https://twitter.com/kelunik)
