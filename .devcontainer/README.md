# Development Container

This repository includes a development container configuration for use with Visual Studio Code and GitHub Codespaces.

## Features

The dev container includes:

- **Python 3.11**: Official Microsoft Python development container image
- **Azure CLI (az)**: Command-line tools for managing Azure resources
- **Azure Developer CLI (azd)**: Tools for Azure application development
- **uv**: Fast Python package installer and resolver

## VS Code Extensions

The following extensions are automatically installed:

- Python language support
- Pylance for enhanced Python IntelliSense
- Azure CLI Tools

## Usage

### With VS Code

1. Install the [Dev Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
2. Open this repository in VS Code
3. Click "Reopen in Container" when prompted, or use Command Palette: `Dev Containers: Reopen in Container`

### With GitHub Codespaces

1. Navigate to the repository on GitHub
2. Click the "Code" button
3. Select "Create codespace on [branch]"

## Verification

Once the container is running, you can verify the installations:

```bash
# Check Python version
python --version

# Check Azure CLI
az --version

# Check Azure Developer CLI
azd version

# Check uv
uv --version
```
