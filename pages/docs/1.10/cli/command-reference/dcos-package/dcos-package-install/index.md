---
layout: layout.pug
title: dcos package install
menuWeight: 1
excerpt: ""
featureMaturity: ""
enterprise: 'no'
navigationTitle:  dcos package install
---

<!-- This source repo for this topic is https://github.com/dcos/dcos-docs -->


# Description
Install a package.

# Usage

```bash
dcos package install <package-name> [OPTION]
```

# Options

| Name, shorthand | Default | Description |
navigationTitle:  dcos package install
|---------|-------------|-------------|
| `--app`   |             |  Application only. |
| `--app-id=<app-id>`   |             |  The application ID. |
| `--cli`   |             |  Command line only. |
| `--options=<file>`   |             | Path to a JSON file that contains customized package installation options. |
| `--package-version=<package-version>`   |             | The package version. |
| `--yes`   |             | Disable interactive mode and assume "yes" is the answer to all prompts. |

# Positional arguments

| Name, shorthand | Default | Description |
navigationTitle:  dcos package install
|---------|-------------|-------------|
| `<package-name>`   |             |  Name of the DC/OS package. |
        
# Parent command

| Command | Description |
navigationTitle:  dcos package install
|---------|-------------|
| [dcos package](/docs/1.10/cli/command-reference/dcos-package/)   | Install and manage DC/OS software packages. |

# Examples

For an example, see the [documentation](/docs/1.10/deploying-services/config-universe-service/).