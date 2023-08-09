# Cache Next Install Action

GitHub action to install Node dependencies and cache the result

## Getting Started

```bash
git clone https://github.com/Andrews-McMeel-Universal/cache-next-install
```

## Installation

To make `cache-next-install` a part of your workflow, just add a step to one of your workflows in your `.github/workflows/` directory in your GitHub repository.

## Options

| Variable            | Description                   | Required | `[Default]` |
| ------------------- | ----------------------------- | :------: | ----------- |
| `node-version`      | Version of Node.js to install |          |             |
| `node-version-file` | Node version file to use      |          | `.nvmrc`    |
