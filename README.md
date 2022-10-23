# Cookiecutter VSCode Python Tools Extensions

Cookiecutter for creating Python VSCode Extension.

![Example](Example.png)

## Features

Based on [ryansonshine/typescript\-npm\-package\-template](https://github.com/ryansonshine/typescript-npm-package-template).

## Getting Started

### 1. Create project using cookiecutter

```shell
py -m venv venv
"venv/scripts/activate"
pip install -U cookiecutter jinja2-strcase
```

```shell
cookiecutter https://github.com/34j/vscode-python-extension-cookiecutter.git
```

### 2. Upload to github

1. Get [Azure DepOps](https://dev.azure.com/) Personal Access Token.
2. Goto [Github repo page]({{cookiecutter.__github_repo_url}}) and [add Actions secrets]({{cookiecutter.__github_repo_url}}/settings/secrets/actions) from `Settings` -> `Secrets` -> `Actions`.
3. `git add -A && git commit -m "chore: Initial Commit"`
4. `npm install`
5. Modify 4 braces (`[], [], [], []`) in `src/extension.ts`.
6. Debug by pressing `F5` and check if it properly works.
7. Modify "keywords" in package.json. (Optional)
8. `git add -A && git commit -m "feat: 

## License Notes

The icon is not MIT Licensed.
