# vscode-workspace-config
My VSCode workspace configuration git repository.
Clone it into the root directory of your project with
```bash
git clone https://github.com/oliverdantzer/vscode-workspace-config.git ./.vscode
```

## What is project workspace configuration?
VSCode's format for a Project-level IDE configuration directory. Contains files such as:
- `settings.json` - IDE settings
- `extensions.json` - Recommended extensions

## What is this repo for?
Use this repo to quickly set up vscode workspace configuration for your projects.

## How do I use this repo?
### Generic version
In the root directory of your project, run
```bash
git clone https://github.com/oliverdantzer/vscode-workspace-config.git ./.vscode
```
### Project-specific branches
To use a branch made for a specific use case:
In the root directory of your project, run
```bash
git clone -b BRANCH-NAME https://github.com/oliverdantzer/vscode-workspace-config.git ./.vscode
```

## Note regarding usage in git repositories
This repository is usually used in git repositories with `.vscode/` listed in their `.gitignore` file. 

> See [the visual studio docs](https://code.visualstudio.com/docs/configure/extensions/extension-marketplace#_workspace-recommended-extensions)
> for the documentation about the **extensions.json** format

> See [the visual studio docs](https://code.visualstudio.com/docs/configure/settings#_settings-json-file)
> for the documentation about the **settings.json** format
