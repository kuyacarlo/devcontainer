# kuyacarlo/devcontainer

Devcontainer counterpart of my workstation's configuration

## Usage

### Recommended

```bash
git submodule add https://github.com/kuyacarlo/devcontainer .devcontainer
```

### Minimal

```bash
mkdir -p .devcontainer && cd .devcontainer # create .devcontainer
curl -O https://raw.githubusercontent.com/kuyacarlo/devcontainer/main/devcontainer.json # copy the spec
curl -O https://raw.githubusercontent.com/kuyacarlo/devcontainer/main/postCreateCommand # copy starter commands
curl -O https://raw.githubusercontent.com/kuyacarlo/devcontainer/main/postStartCommand
```

Then from there, you create and use a codespace. It would automatically setup the tools, but changes/updates require rebuilds.
