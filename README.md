# Hi there 👋

I'm **Tetsuro Mikami** (mickamy), a software engineer based in Tokyo, Japan. I build open-source tools focused on developer productivity, observability, and code quality in the Go ecosystem.

## 🚀 Featured Projects

### [sql-tap](https://github.com/mickamy/sql-tap) ⭐ 874
**Real-time SQL traffic viewer — proxy daemon + TUI client**

`sql-tap` sits between your application and your database (PostgreSQL, MySQL, or TiDB), capturing every query and displaying it in an interactive terminal UI. Inspect queries, view transactions, and run EXPLAIN — all without changing your application code.

- 📊 Real-time query monitoring with beautiful TUI
- 🔍 Transaction tracking and inspection
- ⚡ EXPLAIN and EXPLAIN ANALYZE support
- 🎯 Works with PostgreSQL, MySQL, and TiDB
- 🐳 Docker-ready with native wire protocol support

### [go-sqs-worker](https://github.com/mickamy/go-sqs-worker) ⭐ 15
**A Go library for managing asynchronous jobs using AWS SQS**

A production-ready library that provides a simple, scalable way to produce and consume background jobs with AWS SQS.

- 📦 Producer and Consumer support
- ⏰ Scheduled job processing
- 🔄 Dead Letter Queue integration
- 🛡️ Configurable retry mechanism
- 🌐 LocalStack compatible for local development

### [goimportmaps](https://github.com/mickamy/goimportmaps) ⭐ 26
**Visualize and validate package dependencies in your Go project**

A CLI tool that analyzes your Go project's internal package imports, visualizes them as a dependency graph, and detects architectural violations.

- 📊 Visualize dependencies (Mermaid, Graphviz, HTML)
- 🚨 Detect forbidden imports
- 🛡️ Enforce allowed imports (whitelist)
- 📈 Coupling metrics analysis (Ca, Ce, Instability)
- ✅ Perfect for layered, hexagonal, or clean architecture

### [gopanix](https://github.com/mickamy/gopanix) ⭐ 13
**💥 Visualize your Go panics in the browser**

`gopanix` turns panic stack traces into readable HTML reports, making debugging Go crashes much more comfortable.

- 💥 Automatic panic catching and recovery
- 🌐 Generate HTML reports with stack traces
- 🧪 CLI mode: `gopanix run` and `gopanix test`
- 📦 Library mode: use `defer gopanix.Handle()`
- 🧘 Works without modifying your program

### [contest](https://github.com/mickamy/contest) ⭐ 4
**Lightweight DSL for testing ConnectRPC handlers**

A fluent, expressive testing framework for ConnectRPC that executes handlers directly using Go's `httptest` package.

- 🧪 Direct handler execution without network layer
- 🔄 Automatic `connect.Error` decoding
- ✨ Fluent assertion API
- 🎯 Compatible with Connect interceptors
- 📝 Clean, readable test code

### [injector](https://github.com/mickamy/injector) ⭐ 1
**Type-safe dependency injection code generator for Go**

A command-line tool that generates DI code using Go's type system and a minimal marker tag approach.

- 🔍 Automatic provider discovery
- 🎯 Type-safe dependency resolution
- 🏗️ Interface-first design
- ⚡ Zero runtime reflection
- 📝 Minimal boilerplate code

## 💖 Support My Work

If you find my projects useful, please consider sponsoring! Your support helps me:

- 🛠️ Maintain and improve existing projects
- 🚀 Build new developer tools
- 📚 Create documentation and tutorials
- 🐛 Fix bugs and add new features
- 💬 Provide community support

[![Sponsor on GitHub](https://img.shields.io/badge/Sponsor-❤-ea4aaa?style=for-the-badge&logo=github)](https://github.com/sponsors/mickamy)

Every contribution, no matter the size, makes a difference and is deeply appreciated! 🙏

## 🔗 Connect

- 🐙 GitHub: [@mickamy](https://github.com/mickamy)
- 🏢 Organization: [@RxSwiftCommunity](https://github.com/RxSwiftCommunity)
- 📍 Location: Tokyo, Japan

---

✨ *Thank you for visiting! Feel free to explore my projects, open issues, or submit pull requests.*
