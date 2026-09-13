# Contributing to StackSaga Community

Thanks for your interest in StackSaga! Before opening an issue or pull request, please read this — it explains what kind of contributions this repository accepts and why.

## 📛 Important: This is not the source code repository

`stacksaga-community` does **not** contain the StackSaga framework source code. StackSaga's compiled artifacts are distributed via Maven Central under the `org.stacksaga` group ID, under the [StackSaga Artifact License 1.0 (SSAL-1.0)](./LICENSE.md). That license does not permit modifying, decompiling, or reverse-engineering the Software.

**As a result, we do not accept pull requests that modify, patch, or fork the core framework modules** (`stacksaga-spring-boot-starter`, `stacksaga-kafka-spring-boot-starter`, `stacksaga-mysql-reactive-support`, `stacksaga-cassandra-reactive-support`, `stacksaga-ring-coordinator`, `stacksaga-ring-coordinator-connector`, `stacksaga-trace-window-connector`, or any other core module).

## ✅ What you CAN contribute here

We welcome pull requests and contributions in this repository for:

- **Documentation fixes** — typos, clarity improvements, missing explanations
- **Example projects** — sample Spring Boot applications demonstrating StackSaga usage
- **Reproduction cases** — minimal projects that reproduce a reported bug (attach these to an issue rather than opening a standalone PR, unless asked to do so by a maintainer)
- **Community resources** — FAQs, troubleshooting guides, tutorials

## 🐛 Found a bug in a core module?

Please **do not** attempt to patch it yourself. Instead:

1. Search [existing issues](../../issues) to check it hasn't already been reported.
2. Open a new issue using the [Bug Report template](../../issues/new/choose).
3. Include your StackSaga version, affected module, Spring Boot version, and a minimal reproduction (a linked sample repo is ideal).

Our team will triage, reproduce, and fix it on our side.

## 💡 Have a feature idea?

Open a [Discussion](../../discussions) rather than an issue or PR. If the idea gains traction, we'll track it internally with an `enhancement` label. We don't accept implementation PRs for new features in core modules — but we're always happy to hear ideas.

## 🔒 Found a security issue?

Do not open a public issue or PR. See [SECURITY.md](./SECURITY.md) for how to report it privately.

## 🤝 Code of Conduct

By participating in this community, you agree to abide by our [Code of Conduct](./CODE_OF_CONDUCT.md).

## Questions about this policy?

Contact **info@stacksaga.org**.
