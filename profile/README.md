# DebugBundle

DebugBundle turns production failures into deterministic debugging artifacts that engineers and coding agents can inspect, reproduce, and act on. It captures errors, request context, logs, runtime details, deploy metadata, probes, and related signals, then packages that context into a versioned debug bundle for incident triage and automation.

Use DebugBundle locally while building, connect it to hosted ingestion for team workflows, or wire it into agents through the API, CLI, MCP server, webhooks, alerts, weekly reports, and GitHub automation.

## Start here

| Repository | What it contains |
| --- | --- |
| [`debugbundle`](https://github.com/debugbundle/debugbundle) | Core product source: API, worker, web app, CLI, MCP server, storage, bundle generation, alerts, billing, and email templates. |
| [`site`](https://github.com/debugbundle/site) | Public website, documentation, blog, API/schema artifacts, and launch content. |
| [`debugbundle-js`](https://github.com/debugbundle/debugbundle-js) | JavaScript SDKs for Node.js and browsers. |
| [`action`](https://github.com/debugbundle/action) | Reference GitHub Action for incident automation workflows. |

## SDKs

| Runtime | Repository |
| --- | --- |
| Python | [`debugbundle-python`](https://github.com/debugbundle/debugbundle-python) |
| PHP | [`debugbundle-php`](https://github.com/debugbundle/debugbundle-php) |
| WordPress | [`debugbundle-wordpress`](https://github.com/debugbundle/debugbundle-wordpress) |
| Java | [`debugbundle-java`](https://github.com/debugbundle/debugbundle-java) |
| Go | [`debugbundle-go`](https://github.com/debugbundle/debugbundle-go) |
| Ruby | [`debugbundle-ruby`](https://github.com/debugbundle/debugbundle-ruby) |
| Android | [`debugbundle-android`](https://github.com/debugbundle/debugbundle-android) |
| Swift | [`debugbundle-swift`](https://github.com/debugbundle/debugbundle-swift) |
| React Native | [`debugbundle-react-native`](https://github.com/debugbundle/debugbundle-react-native) |
| .NET | [`debugbundle-dotnet`](https://github.com/debugbundle/debugbundle-dotnet) |

## Interfaces

- **API** for ingestion, retrieval, project management, alerts, webhooks, probes, billing, and GitHub automation.
- **CLI** for setup, local processing, cloud verification, incident inspection, bundle retrieval, and operations.
- **MCP server** for coding agents that need structured access to incidents, bundles, projects, probes, and automation.
- **Web app** for project operations, incident review, improvement opportunities, settings, alerts, webhooks, and billing.

## Learn more

- Website and docs: [`debugbundle.com`](https://debugbundle.com)
- Core repository: [`github.com/debugbundle/debugbundle`](https://github.com/debugbundle/debugbundle)
