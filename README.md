# AI Prompt Library

A comprehensive library for capturing, storing, and generating AI prompts for Cursor and Raycast.

## Overview

This repository serves as a centralized collection of AI prompts, custom modes, and configurations for:

- **Cursor**: Custom modes and project rules
- **Raycast**: AI Chat Presets and AI Commands

## Project Structure

```
ai-prompts/
├── .cursor/
│   └── rules/             # Local Cursor Project Rules (.mdc files)
├── cursor-modes/          # Cursor Custom Modes (.txt files)
├── cursor-project-rules/  # Cursor Project Rules (.mdc files)
├── raycast-presets/       # Raycast AI Chat Presets (.json files)
├── raycast-commands/      # Raycast AI Commands (.json files)
├── README.md              # Main project documentation
└── LICENSE.md             # Project license
```

## File Types

- **`.txt`** - Plain text prompts and Cursor custom modes
- **`.json`** - Structured data for Raycast AI Chat Presets and Commands
- **`.mdc`** - Cursor-specific project rules and configurations

## Getting Started

1. **Clone the repository**
2. **Browse categories** based on your needs
3. **Copy prompts** to your local Cursor/Raycast configuration
4. **Customize** prompts for your specific use cases
5. **Contribute** new prompts back to the community

## Categories

### Cursor

- **Custom Modes**: Specialized AI modes for specific tasks
- **Project Rules**: Context-aware rules for different project types

### Raycast

- **AI Chat Presets**: Pre-configured chat templates
- **AI Commands**: Specialized commands for automation

## Contributing

1. Follow the established file naming conventions
2. Test prompts in actual environments before submitting
3. Include clear documentation and usage examples
4. Use appropriate file types and formatting standards
5. Update relevant documentation

## Resources

- [Cursor Custom Modes Documentation](https://docs.cursor.com/agent/modes#custom)
- [Cursor Project Rules Documentation](https://docs.cursor.com/context/rules#project-rules)
- [Raycast AI Documentation](https://manual.raycast.com/ai#block-1cfd6e4a821581f99273f9f81d0ba4fe)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Ideas

- [ ] Add an api to generate prompts
- [ ] Bulid a Raycast Extension to generate prompts with these prompts
