# Unto Labs

We build **Thru**, an L1 blockchain for Rust programs, built on RISC-V. Programs compile
to standard RISC-V and run on the Thru VM: no custom bytecode, no compiler fork. C is the
documented path for writing programs today; a Rust program SDK ships in-tree.

## Start here

| | |
|---|---|
| **Documentation** | <https://thru.org/docs/> (agent index: <https://thru.org/llms.txt>) |
| **Set up the DevKit** | <https://thru.org/docs/program-development/setting-up-thru-devkit/> |
| **Source** | [Unto-Labs/thru](https://github.com/Unto-Labs/thru): C, C++, and Rust SDKs, the `thru` CLI, Rust client crates, protobufs, and TypeScript packages |
| **Explorer** | <https://scan.thru.org> |

## Packages and tools

- **CLI**: `npm i -g thru` or `cargo install thru`. Linux packages and SDK/toolchain
  tarballs ship with every [release](https://github.com/Unto-Labs/thru/releases).
- **Rust crates**: [`thru-client`](https://crates.io/crates/thru-client),
  [`thru-grpc-client`](https://crates.io/crates/thru-grpc-client),
  [`thru-base`](https://crates.io/crates/thru-base).
- **TypeScript**: [`@thru/sdk`](https://www.npmjs.com/package/@thru/sdk) and the other
  `@thru/*` packages on npm.
- **Explorer MCP**: `https://scan.thru.org/api/mcp`, listed as `org.thru/thru-explorer` in
  the [MCP registry](https://registry.modelcontextprotocol.io/?q=org.thru).

## Get in touch

- X: [@thru_xyz](https://x.com/thru_xyz)
- Company: <https://untolabs.com>
- Issues and proposals: [Unto-Labs/thru](https://github.com/Unto-Labs/thru/issues)
