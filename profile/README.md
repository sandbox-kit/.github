# Sandbox Kit

### One SDK. Any sandbox provider.

Sandbox Kit is an open-source, multi-language SDK for creating and managing sandboxes across infrastructure providers.

Build against a consistent interface without coupling your application to one provider.

## Why Sandbox Kit?

Sandbox providers differ in their APIs, configuration, lifecycle operations, and language support. Sandbox Kit offers shared contracts and consistent semantics while keeping provider-specific capabilities explicit.

- **Provider-agnostic:** Integrate with multiple providers through a common SDK interface.
- **Multi-language:** Shared contracts across Go and TypeScript.
- **Unified lifecycle:** Create, retrieve, and manage sandboxes through supported operations.
- **Provider-aware:** Validate options and surface capability differences rather than silently ignoring them.
- **Open source:** MIT-licensed and built in the open.

## Current support

| | |
| --- | --- |
| **Providers** | Daytona, Modal |
| **Languages** | Go, TypeScript |
| **Features** | Authentication, sandbox creation, supported lifecycle operations, validation, metadata, common error kinds |
| **License** | MIT |

Execution, storage, GPU requests, and harness integrations are planned, not yet implemented.

## Get started

Explore **[sandbox-kit/kit](https://github.com/sandbox-kit/kit)** for examples, documentation, and contribution instructions.

We welcome feedback, issues, and contributions as we expand provider and language support.
