# DebugBundle

DebugBundle captures runtime failures, groups them into incidents, and publishes deterministic debug bundles for humans and AI agents.

## Start here

| Repository | What it contains |
| --- | --- |
| [`debugbundle`](https://github.com/debugbundle/debugbundle) | Core product source: API, worker, web app, CLI, MCP server, storage, bundle generation, alerts, billing, and email templates. |
| [`site`](https://github.com/debugbundle/site) | Public website, documentation, blog, API/schema artifacts, and launch content. |
| [`debugbundle-js`](https://github.com/debugbundle/debugbundle-js) | JavaScript SDKs for Node.js and browsers. |
| [`action`](https://github.com/debugbundle/action) | Reference GitHub Action for incident automation workflows. |

## SDKs

All SDKs follow the same universal interface: `init`, `captureException`, `captureError`, `captureLog`, `captureRequest`, `captureMessage`, `setContext`, `probe`, and `flush`.

| Runtime | Package | Repository |
| --- | --- | --- |
| Node.js | `@debugbundle/sdk-node` | [`debugbundle-js`](https://github.com/debugbundle/debugbundle-js) |
| Browser | `@debugbundle/sdk-browser` | [`debugbundle-js`](https://github.com/debugbundle/debugbundle-js) |
| Python | `debugbundle-python` | [`debugbundle-python`](https://github.com/debugbundle/debugbundle-python) |
| PHP | `debugbundle/sdk-php` | [`debugbundle-php`](https://github.com/debugbundle/debugbundle-php) |
| Java | `com.debugbundle:debugbundle-spring-boot-starter` | [`debugbundle-java`](https://github.com/debugbundle/debugbundle-java) |
| .NET | `DebugBundle.AspNetCore` / `DebugBundle.Sdk` | [`debugbundle-dotnet`](https://github.com/debugbundle/debugbundle-dotnet) |
| Go | `github.com/debugbundle/debugbundle-go` | [`debugbundle-go`](https://github.com/debugbundle/debugbundle-go) |
| Ruby | `debugbundle` | [`debugbundle-ruby`](https://github.com/debugbundle/debugbundle-ruby) |
| Android | `com.debugbundle:debugbundle-android` | [`debugbundle-android`](https://github.com/debugbundle/debugbundle-android) |
| Swift | `DebugBundle` | [`debugbundle-swift`](https://github.com/debugbundle/debugbundle-swift) |
| React Native | `@debugbundle/sdk-react-native` | [`debugbundle-react-native`](https://github.com/debugbundle/debugbundle-react-native) |
| WordPress | `debugbundle-wordpress` | [`debugbundle-wordpress`](https://github.com/debugbundle/debugbundle-wordpress) |

## Interfaces

- **API** for ingestion, retrieval, project management, alerts, webhooks, probes, billing, and GitHub automation.
- **CLI** for setup, local processing, cloud verification, incident inspection, bundle retrieval, and operations.
- **MCP server** for coding agents that need structured access to incidents, bundles, projects, probes, and automation.
- **Web app** for project operations, incident review, improvement opportunities, settings, alerts, webhooks, and billing.

## Learn more

- Website and docs: [`debugbundle.com`](https://debugbundle.com)
- Core repository: [`github.com/debugbundle/debugbundle`](https://github.com/debugbundle/debugbundle)
