# Cache Next Install Action

This GitHub action allows you to install Node.js dependencies and cache the result, improving the efficiency of your workflows.

## Getting Started

To get started, clone the repository using the following command:

```bash
git clone https://github.com/Andrews-McMeel-Universal/cache-next-install
```

## Installation

To integrate `cache-next-install` into your workflow, add a step to one of your workflows in the `.github/workflows/` directory of your GitHub repository.

## Configuration Options

You can customize the behavior of `cache-next-install` using the following variables:

| Variable            | Description                   | Required | Default |
| ------------------- | ----------------------------- | :------: | ------- |
| `node-version`      | Specifies the version of Node.js to install. If not provided, the latest version is used. | No | Latest version |
| `node-version-file` | Specifies the Node version file to use. This is useful if you want to specify a particular version of Node.js in a file. | No | `.nvmrc` |