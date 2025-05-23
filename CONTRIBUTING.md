# Contributing Guidelines for Unofficial Fabula Ultima System (Project FU)

## Introduction

Welcome to the contribution guidelines for Project FU! We appreciate your interest in improving our system. Please follow the guidelines below for code and content contributions.

## Communication Channels

If you have any questions or concerns, feel free to reach out to us through the following channels:

- Discord: [Rooster Games Discord](https://discord.gg/G9qGbn2) - `#bot-and-tool-discussion` channel
- Discord: [Project FU Discord](https://discord.gg/SNuxpzCgVB) - `#support` channel

## Submitting Issues

Issues reported on [GitHub](https://github.com/League-of-Fabulous-Developers/FoundryVTT-Fabula-Ultima/issues) and support channels will be reviewed and tracked on our [Trello Board](https://trello.com/b/VEa8VQHc/fabula-ultima-system). Please follow the guidelines below for different types of issues.

### Bugs

Before submitting a bug report, ensure the following:

- Bugs are reproducible without active modules. If module-related, contact the module author.
- Provide relevant hosting details.
- Include clear instructions on reproducing the issue and the expected vs actual outcome.

## Tooling and Setup

Project FU is based on the [Boilerplate Template](https://foundryvtt.wiki/en/development/guides/SD-tutorial/SD01-Getting-started), using plain JavaScript and [Gulp](https://gulpjs.com/) for build tasks.
Visit [here](https://github.com/League-of-Fabulous-Developers/FoundryVTT-Fabula-Ultima/wiki/Development-Environment) for setting up an development environment for the system.

### Branches

- **main:** Mainline branch for v12 releases and above.
- **dev:** Primary development branch.

When opening a PR, ensure it goes into the dev branch.

### Prerequisite Software

- [Git](https://git-scm.com/)
- [Node.js LTS](https://nodejs.org)
- Code editor (recommended: [Visual Studio Code](https://code.visualstudio.com/))

### Setup

Clone the repository and run:

```bash
npm install
```

### Building from Source

Start the build process in watch mode:

```bash
npm run watch
```

Or for a one-time build:

```bash
npm run build
```

Enable the _Hot-Reload Package Files_ option in your Foundry application configuration for an improved developer experience.

### Localization

When making changes to the localization google sheet, please run the following:

```bash
npm run localize
```

## Code Contributions

To contribute code, [fork the repository](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo) and submit a [pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests).
