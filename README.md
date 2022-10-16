# Cookiecutter VSCode Python Tools Extensions

Cookiecutter for a VS Code extension for your favorite python tool. Linter, Formatter, or Code Analysis, or all of those together.

![Example](Example.png)

## Requirements

1. cookkiecutter

## Features

Based on [ryansonshine/typescript\-npm\-package\-template](https://github.com/ryansonshine/typescript-npm-package-template).

## Getting Started

### 1. Create project using cookiecutter

```shell
py -m venv venv
"venv/scripts/activate"
pip install -U cookiecutter jinja2-strcase
git clone https://github.com/34j/vscode-python-tools-extension-template-cookiecutter.git
cookiecutter ./vscode-python-tools-extension-template-cookiecutter
```

Once you have installed,

```shell
"venv/scripts/activate"
cookiecutter ./vscode-python-tools-extension-template-cookiecutter
```

### 2. Upload to github

1. Get [Azure DepOps](https://dev.azure.com/) Personal Access Token.
2. Goto [Github repo page]({{cookiecutter.__github_repo_url}}) and [add Actions secrets]({{cookiecutter.__github_repo_url}}/settings/secrets/actions) from `Settings` -> `Secrets` -> `Actions`.
