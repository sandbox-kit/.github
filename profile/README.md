# Sandbox Kit

We build open-source tools for **agent sandboxes**: a pluggable SDK for cloud runtimes and provider integrations, and **[sandbox.directory](https://sandbox.directory)**—a searchable list of sandbox products for AI agents.

## [sandbox.directory](https://sandbox.directory)

Curated directory of agent sandbox providers (hosted runtimes, browsers, VMs, self-hosted options). Open the site, search, and jump to each vendor—no account required.

| | |
| --- | --- |
| **Site** | [sandbox.directory](https://sandbox.directory) |
| **Source** | [sandbox-kit/directory](https://github.com/sandbox-kit/directory) |
| **License** | MIT |

## Sandbox Kit SDK

The SDK ships libraries, shared contracts, and provider integrations for creating and managing cloud sandboxes from TypeScript and Go.

### Libraries

TypeScript packages are on npm.

| Package | Install |
| --- | --- |
| [`@sandbox-kit/sandbox`](https://www.npmjs.com/package/@sandbox-kit/sandbox) | `npm install @sandbox-kit/sandbox` |
| [`@sandbox-kit/daytona`](https://www.npmjs.com/package/@sandbox-kit/daytona) | `npm install @sandbox-kit/daytona` |
| [`@sandbox-kit/modal`](https://www.npmjs.com/package/@sandbox-kit/modal) | `npm install @sandbox-kit/modal` |

Install the core package and the provider you use.

Go modules are in [sandbox-kit/kit](https://github.com/sandbox-kit/kit):

```sh
go get github.com/sandbox-kit/kit/sdks/go/sandbox@latest
go get github.com/sandbox-kit/kit/sdks/go/providers/daytona@latest
# or: go get github.com/sandbox-kit/kit/sdks/go/providers/modal@latest
```

### Also in the kit repo

- Shared protobuf contracts for create, config, lifecycle, and errors
- Daytona and Modal provider packages for TypeScript and Go
- The `sandbox-kit` CLI for tests and contract generation
- Runnable examples and guides

| | |
| --- | --- |
| **Providers** | Daytona, Modal |
| **Languages** | TypeScript, Go |
| **License** | MIT |

## Start here

| Project | Link |
| --- | --- |
| **Provider directory** | [sandbox.directory](https://sandbox.directory) · [sandbox-kit/directory](https://github.com/sandbox-kit/directory) |
| **SDK, examples, docs** | [sandbox-kit/kit](https://github.com/sandbox-kit/kit) |

Issues and pull requests are welcome.