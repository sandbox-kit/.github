# Sandbox Kit

Open-source tools for **agent sandboxes**: discover vendors in public, then wire one provider—or switch later—in your app with a shared SDK.

## What we ship

| | **[sandbox.directory](https://sandbox.directory)** | **[Sandbox Kit](https://github.com/sandbox-kit/kit)** |
| --- | --- | --- |
| **Purpose** | Find and compare sandbox providers | Create and manage sandboxes in code |
| **Audience** | Builders evaluating runtimes | Agents and platforms integrating sandboxes |
| **Languages** | Web app (no install) | TypeScript, Go |
| **License** | MIT | MIT |

---

## sandbox.directory

Searchable directory of agent sandbox products—hosted runtimes, browser sandboxes, VMs, and self-hosted options.

| | |
| --- | --- |
| **Site** | [sandbox.directory](https://sandbox.directory) |
| **Repository** | [sandbox-kit/directory](https://github.com/sandbox-kit/directory) |

**Typical use:** pick or validate a vendor before you integrate. Search by product name or keyword; open vendor links from the list. No account required.

[Open the directory](https://sandbox.directory) · [Suggest a provider](https://github.com/sandbox-kit/directory/issues/new)

---

## Sandbox Kit SDK

Multi-provider SDK with one client surface for create/lifecycle, filesystem, and process APIs. Change vendor by swapping the provider package—not your app logic.

**Providers:** Blaxel · Daytona · Modal

| | |
| --- | --- |
| **Repository** | [sandbox-kit/kit](https://github.com/sandbox-kit/kit) |
| **Documentation** | [sandbox-kit.github.io/kit/docs](https://sandbox-kit.github.io/kit/docs) |
| **Examples** | [kit/examples](https://github.com/sandbox-kit/kit/tree/main/examples) |

### Quick install

Install the **core** package and **one** provider adapter.

**TypeScript**

```sh
npm install @sandbox-kit/sandbox @sandbox-kit/daytona
# or: @sandbox-kit/blaxel · @sandbox-kit/modal
```

| npm package | Role |
| --- | --- |
| [`@sandbox-kit/sandbox`](https://www.npmjs.com/package/@sandbox-kit/sandbox) | Core `Client` |
| [`@sandbox-kit/blaxel`](https://www.npmjs.com/package/@sandbox-kit/blaxel) | Blaxel |
| [`@sandbox-kit/daytona`](https://www.npmjs.com/package/@sandbox-kit/daytona) | Daytona |
| [`@sandbox-kit/modal`](https://www.npmjs.com/package/@sandbox-kit/modal) | Modal |

**Go** (requires Go 1.26+)

```sh
go get github.com/sandbox-kit/kit/sdks/go/sandbox@latest
go get github.com/sandbox-kit/kit/sdks/go/providers/daytona@latest
# providers: blaxel · daytona · modal
```

### What’s in the kit repo

- Shared protobuf contracts (create, config, lifecycle, errors)
- Provider adapters for TypeScript and Go
- `sandbox-kit` CLI for tests and contract generation
- Runnable examples per provider

Full tutorials and API detail live in the **[docs site](https://sandbox-kit.github.io/kit/docs)**—start there after install.

---

## Contribute

Open an issue or pull request on [directory](https://github.com/sandbox-kit/directory) or [kit](https://github.com/sandbox-kit/kit). Contributions are welcome.