# Pre-commit Hook Manager

Manage pre-commit hooks to automate code checks before every commit.

## Features

- ⚡ **Easy Installation**: One command to install hooks
- 🔧 **Customizable**: Skip tests or linting as needed
- 📋 **Staged Files**: Check only staged files
- 🔗 **GitHub Actions**: Generate workflows

## Installation

```bash
npm install
```

## Usage

```bash
# Install hook
node src/index.js install

# Install without tests
node src/index.js install --skip-tests

# Check staged files
node src/index.js check

# List hooks
node src/index.js list

# Uninstall
node src/index.js uninstall

# Generate GitHub Actions
node src/index.js action
```

## How It Works

The hook runs before each commit and checks staged files. You can configure which checks to run.

## License

MIT
