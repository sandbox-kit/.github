# Sandbox Kit

An organization committed to building open-source tools for cloud sandboxes.

Sandbox Kit publishes libraries, shared contracts, and provider integrations for creating and managing cloud sandboxes from TypeScript and Go.

## Libraries

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

## Also in the kit repo

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

Source, examples, and docs: **[sandbox-kit/kit](https://github.com/sandbox-kit/kit)**.

Issues and pull requests are welcome.
