# Extension Designer Plugin

Expert guidance for creating effective Claude Code extensions following production best practices.

## What This Does

Provides automatic, intelligent guidance when creating Skills, Agents, Commands, Hooks, or Plugins for Claude Code. Auto-activates when you discuss extension design.

## Features

- **Decision Framework**: Helps choose the right extension type
- **Best Practices**: Production-proven patterns and anti-patterns
- **Auto-Activation**: Appears when you need it
- **Implementation Templates**: Complete, working examples
- **Optional Guided Workflow**: `/create-extension` command for step-by-step creation

## Installation
```bash
# Add marketplace
/plugin marketplace add yourusername/claude-extensions

# Install plugin
/plugin install extension-designer@yourusername
```

## Usage

### Automatic (Skill)

Just start discussing extension creation:
- "I want to create a skill for X"
- "Should this be an agent or a skill?"
- "Help me design a hook for Y"

The extension-designer skill automatically activates and guides you.

### Guided Workflow (Command)

For a structured, interactive process: