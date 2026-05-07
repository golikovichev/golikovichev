### Hi, I am Mikhail

QA engineer based in Hove, UK. I work on Python test tooling, mostly around pytest and the boring problems testers face every day: brittle test data, slow integration suites, and the gap between Postman collections and proper test code.

### What I am building right now

**[postman2pytest](https://github.com/golikovichev/postman2pytest)** — converts Postman v2 collections into runnable pytest test suites. Handles auth headers, body schemas, environment variables, and emits parametrised pytest with fixtures. MIT-licensed, on PyPI.

[![PyPI](https://img.shields.io/pypi/v/postman2pytest.svg)](https://pypi.org/project/postman2pytest/) [![CI](https://github.com/golikovichev/postman2pytest/actions/workflows/ci.yml/badge.svg)](https://github.com/golikovichev/postman2pytest/actions)

**[secure-log2test](https://github.com/golikovichev/secure-log2test)** — generates pytest regression tests from anonymised Kibana log exports. Useful when you want a fast smoke-test layer that mirrors real production traffic patterns without leaking PII. Auth headers are redacted by default.

**[pytest-conversational](https://github.com/golikovichev/pytest-conversational)** — a smaller experiment in deterministic conversational testing without LLMs. Treats chat turns as parametrised pytest cases with explicit state assertions.

### Tech I reach for

Python · pytest · Selenium · Postman · requests · jinja2 · GitHub Actions · pyproject + console_scripts packaging · Grafana / Kibana for triage · SQL for data validation.

### Writing

- Dev.to: [Postman and pytest are living in parallel universes. Here is a bridge.](https://dev.to/golikovichev/postman-and-pytest-are-living-in-parallel-universes-heres-a-bridge-5bgn) — walkthrough of how postman2pytest came together.
- Hashnode: [same article, different audience](https://golikovichevhashnodedev.hashnode.dev/postman-and-pytest-are-living-in-parallel-universes-here-s-a-bridge).

### How I work

Sole QA on backend e-commerce. I own API testing across 12+ Postman collections, a regression suite of 200+ test cases, and an internal Python automation framework I built (Selenium + pytest + POM). Most of my time goes into root cause analysis with Grafana / Kibana / SQL, and pushing back on flaky tests so they stop costing the team momentum.

### Where to find me

- GitHub Discussions: I lurk and occasionally chime in on pytest-dev threads.
- Dev.to: [dev.to/golikovichev](https://dev.to/golikovichev)

If you spot a real bug in any of the tools above, opening an issue is the fastest way to my attention.
