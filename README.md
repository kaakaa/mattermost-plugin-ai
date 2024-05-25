# Mattermost AI Copilot Plugin

> Mattermost plugin for local and third-party LLMs

![The Mattermost Copilot AI Plugin is an extension for mattermost that provides functionality for local and third-party LLMs](https://github.com/mattermost/openops/assets/7295363/37cc5337-16a0-4d88-971f-71cd0cdc52e9)

<!-- omit from toc -->
## Table of Contents

- [Background](#background)
- [Contributing](#contributing)
- [License](#license)

## Background

The Mattermost AI Copilot Plugin adds functionality for local (self-hosted) and third-party (vendor-hosted) LLMs within Mattermost v9.6 and above. This plugin is currently experimental. 

Contributions and suggestions are welcome. See the [Contributing](#contributing) section for more details!

Join the discussion in the [~AI-Exchange channel](https://community.mattermost.com/core/channels/ai-exchange) and explore the [Discourse forum](https://forum.mattermost.com/c/openops-ai/40). 💬

## Install

We recommend using Mattermost Server v9.6 or later for the best experience. Compatible Mattermost server versions include:

- v9.6 or later
- v9.5.2+ ([ESR](https://docs.mattermost.com/deploy/mattermost-changelog.html#release-v9-5-extended-support-release))
- v9.4.4+
- v9.3.3+
- v8.1.11+ ([ESR](https://docs.mattermost.com/deploy/mattermost-changelog.html))

See the [Mattermost Product Documentation](https://docs.mattermost.com/configure/enable-ai-copilot.html) for details on installing, configuring, enabling, and using this Mattermost integration.

**Note**: Installation instructions assume you already have [Mattermost Server](https://mattermost.com/download/) installed and configured with [PostgreSQL](https://www.postgresql.org/).

## Contributing

Interested in contributing to our open source project? Start by reviewing the [contributor guidelines](./.github/CONTRIBUTING.md) for this repository. See the [Developer Setup Guide](docs/developer-setup-guide.md) for details on setting up a Mattermost instance for development.

## License

This repository is licensed under [Apache-2](./LICENSE), except for the [server/enterprise](server/enterprise) directory which is licensed under the [Mattermost Source Available License](LICENSE.enterprise). See [Mattermost Source Available License](https://docs.mattermost.com/overview/faq.html#mattermost-source-available-license) to learn more.
