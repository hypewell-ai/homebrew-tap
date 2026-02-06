# Hypewell Homebrew Tap

Homebrew formulae for Hypewell tools.

## Installation

```bash
brew tap hypewell-ai/tap
brew install hy
```

## Available Formulae

| Formula | Description |
|---------|-------------|
| `hy` | CLI for Hypewell Studio |

## Usage

After installation:

```bash
# Login to Hypewell Studio
hy auth login

# List productions
hy productions list

# Create a production
hy productions create --name "My Video" --topic "Product demo"

# Chat with AI assistant
hy thread chat "Help me write a script"
```

## Documentation

- [Hypewell Studio](https://studio.hypewell.ai)
- [API Documentation](https://studio.hypewell.ai/docs)
