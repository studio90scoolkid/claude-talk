# AI Debate Arena

Two AI agents debate any topic in a retro RPG-style interface, powered by Claude CLI.

## Features

- **Two AI Agents**: Watch two Claude-powered agents debate any topic in real time
- **Retro RPG UI**: Pixel-art characters with sprite animations in a classic RPG battle layout
- **Customizable Personas**: Set each agent as Pro, Neutral, or Con
- **Model Selection**: Choose between Haiku, Sonnet, or Opus for each agent
- **Custom Names**: Give each agent a custom display name
- **30+ Languages**: Full i18n support for the UI
- **Smart Context**: History summarization keeps debates fresh and avoids repetition
- **Settings Persistence**: Your last configuration is saved automatically

## Requirements

- [Claude CLI](https://docs.anthropic.com/en/docs/claude-cli) must be installed and authenticated
- VS Code 1.85.0 or later

## Usage

1. Open the Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`)
2. Run **AI Debate: Start Debate Arena**
3. Enter a debate topic, choose personas and models
4. Click **START** and watch the debate unfold

## How It Works

Each agent takes turns responding to the other using Claude CLI in one-shot mode. The extension manages context by summarizing older turns, keeping recent exchanges in full detail, and providing turn-aware strategy hints to ensure diverse, non-repetitive arguments.

## Made by

**STUDIO COOLKID**

## License

[MIT](LICENSE)
