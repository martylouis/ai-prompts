# AI Prompt Library

A comprehensive library for capturing, storing, and generating AI prompts for Cursor and Raycast.

## Overview

This repository serves as a centralized collection of AI prompts, custom modes, and configurations for:

- **Cursor**: System instructions and project rules
- **Raycast**: AI Chat Presets and AI Commands

## Getting Started

1. **Clone the repository**
2. **Browse categories** based on your needs
3. **Copy prompts** to your local Cursor/Raycast configuration
4. **Customize** prompts for your specific use cases
5. **Contribute** new prompts back to the community

## Categories

### Cursor

- **System Instructions**: Specialized AI roles and expertise areas
  - [Code Reviewer](system-instructions/code-reviewer.md) - Expert code analysis and review
  - [Technical Writer](system-instructions/technical-writer.md) - Professional technical documentation
  - [System Level Architect](system-instructions/system-level-architect.md) - High-level system design
  - [PRD Generator](system-instructions/prd-generator.md) - Product requirements documentation
  - [UX Design Brief Generator](system-instructions/ux-design-brief-generator.md) - User experience design briefs
- **Project Rules**: Context-aware rules for development workflows
  - [Project Structure](.cursor/rules/project-structure.mdc) - Overall project organization
  - [Coding Standards](.cursor/rules/coding-standards.mdc) - Code quality and style guidelines
  - [Contribution Guidelines](.cursor/rules/contribution-guidelines.mdc) - Development workflow standards

### Raycast

- **AI Chat Presets**: Pre-configured chat templates
  - [Technical Writer](raycast-presets/technical-writer.json) - Professional documentation assistance
  - [System Level Prompt Architect](raycast-presets/system-level-prompt-architect.json) - Prompt engineering expertise
  - [UX Design Brief Specialist](raycast-presets/ux-design-brief-specialist.json) - UX design and research
- **AI Commands**: Specialized commands for automation
  - [Generate API Docs](raycast-commands/json/generate-api-docs.json) - API documentation generation
  - [Git Conventional Commit Message](raycast-commands/json/git-conventional-commit-message.json) - Conventional commit formatting
  - [Git Short Commit Message](raycast-commands/json/git-short-commit-message.json) - Concise commit messages

## Project Structure

```
ai-prompts/
├── .cursor/rules/        # Cursor project rules
├── raycast-commands/     # Raycast AI commands
│   ├── json/             # Machine-readable configurations
│   └── md/               # Human-readable documentation
├── raycast-presets/      # Raycast AI chat templates
├── system-instructions/  # Cursor system prompts
└── README.md             # Project documentation
```

## Contributing

1. Follow the established file naming conventions
2. Test prompts in actual environments before submitting
3. Include clear documentation and usage examples
4. Use appropriate file types and formatting standards
5. Update relevant documentation

### Development Guidelines

- **File Naming**: Use kebab-case for all filenames
- **Documentation**: Every JSON file should have a corresponding MD file
- **Testing**: Verify prompts work in target environments
- **Structure**: Maintain parallel organization between JSON and MD directories

## Resources

- [Cursor Custom Modes Documentation](https://docs.cursor.com/agent/modes#custom)
- [Cursor Project Rules Documentation](https://docs.cursor.com/context/rules#project-rules)
- [Raycast AI Documentation](https://manual.raycast.com/ai#block-1cfd6e4a821581f99273f9f81d0ba4fe)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Future Ideas

- [ ] Add an API to generate prompts
- [ ] Build a Raycast Extension to generate prompts with these prompts
