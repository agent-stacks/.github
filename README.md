# Agent Stacks

Agent Stacks makes AI-agent tooling easier to compose, reproduce, and
distribute.

A **stack** is an agent client, the plugins and skills it uses, and the
runtimes those components need, built and delivered as one unit. We define the
conventions for these components and provide the tooling to build them as
reproducible packages.

## What we work on

- **Specifications** — The
  [Agent Stacks Specification](https://github.com/agent-stacks/agent-stacks-spec)
  describes how a stack composes Agent Plugins, Agent Skills, and the Model
  Context Protocol, and defines what a stack adds on top.
- **Tooling** — [agent-stacks-cli](https://github.com/agent-stacks/agent-stacks-cli)
  imports, builds, and launches stacks.
- **Packages** — [agent-pkgs](https://github.com/agent-stacks/agent-pkgs)
  provides reproducible Nix packages for plugins, skills, MCP servers, and
  their runtimes.
- **Documentation** — [agent-stacks.org](https://agent-stacks.org) is the home
  for project documentation and announcements.

## Get involved

Start with the [specification](https://github.com/agent-stacks/agent-stacks-spec)
and its [current draft](https://github.com/agent-stacks/agent-stacks-spec/blob/main/spec/0.1.0.md).
Issues and pull requests are welcome in the repository most relevant to your
idea.

## License

Each repository documents its own license. Packaged plugins retain their
upstream licenses.
