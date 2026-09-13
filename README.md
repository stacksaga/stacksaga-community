
<picture>
  <source media="(prefers-color-scheme: dark)" srcset=".github/stacksaga-light.png">
  <source media="(prefers-color-scheme: light)" srcset=".github/stacksaga-dark.png">
  <img alt="StackSaga Logo" src=".github/assets/logo-light.png" width="200">
</picture>

# StackSaga Community

Community hub for StackSaga — bug reports, discussions, and docs for all StackSaga framework modules.

StackSaga is a distributed saga orchestration framework for Spring Boot, supporting synchronous and Kafka-based event-driven transport, and MySQL, PostgreSQL, and Cassandra/ScyllaDB backends.

> **This repository does not contain the StackSaga source code.** It exists for bug reports, community discussion, and documentation. StackSaga's compiled artifacts are published to Maven Central under the `org.stacksaga` group ID.

## 📄 License

StackSaga is distributed under the **StackSaga Artifact License 1.0 (SSAL-1.0)**. Key points:

- ✅ Free to use — internal, development, testing, and commercial production
- ✅ Free to embed as an unmodified dependency in your own applications
- ❌ No modification, decompiling, or reverse-engineering
- ❌ No redistribution outside official Maven Central
- ❌ No SaaS / managed hosting without a separate commercial license
- 📛 Requires visible "Powered by StackSaga" attribution — see [Attribution](#-attribution) below

Full license text: [LICENSE](./LICENSE.md)

## 🐛 Reporting a Bug

1. **Search first** — check [open and closed issues](../../issues) to avoid duplicates.
2. **Use the bug report template** when opening a new issue — include your StackSaga version, affected module, Spring Boot version, transport/database type, minimal reproduction steps, and relevant logs.
3. Since modification of the Software isn't permitted under the license, please report defects here rather than submitting a patch — we'll take it from there.

👉 [Open a bug report](../../issues/new/choose)

## 💬 Discussions

Questions, ideas, and general help go in [Discussions](../../discussions), not Issues. Issues are reserved for confirmed or suspected bugs.

## 🔒 Reporting a Security Issue

Please **do not** open a public issue for security vulnerabilities. Use [GitHub Security Advisories](../../security/advisories/new) for private, responsible disclosure. We aim to respond on a best-effort basis; commercial support subscribers receive prioritized handling.

## 🛠️ Support

| | Community (Free) | Commercial Support |
|---|---|---|
| Use in production | ✅ | ✅ |
| Public issue tracker | ✅ | ✅ |
| Response time | Best-effort | Prioritized |
| Security patches | Best-effort | Included |
| Direct technical assistance | ❌ | ✅ |

Interested in commercial support or a SaaS/managed-hosting license? Contact **info@stacksaga.org**.

## 🏷️ Attribution

If you use StackSaga in a product, service, or application, please include a visible credit:

```
Powered by StackSaga — https://stacksaga.org
```

Place it in your README, about/credits page, or public documentation.

## 🔗 Links

- Documentation: [docs.stacksaga.org](https://docs.stacksaga.org)
- Maven Central: `org.stacksaga`
- Website: [PROJECT_WEBSITE_URL]

## 📜 Code of Conduct

This community follows a [Code of Conduct](./CODE_OF_CONDUCT.md). Please read it before participating.
