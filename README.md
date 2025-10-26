# Claude Skills

A collection of custom skills for Claude Code that extend Claude's capabilities for specific workflows and domains.

## What are Skills?

Skills are specialized knowledge packages that help Claude perform tasks more effectively. Each skill contains:
- **SKILL.md**: The main skill definition with instructions and best practices
- **References**: Supporting documentation and examples
- **Assets**: Templates, stylesheets, or other resources

## Available Skills

### 1. btppt - Billtrust PowerPoint Creation
Professional presentation creation following Billtrust 2025 brand standards with modern design patterns, precise color schemes, and optimized layouts for executive audiences.

**Location**: `btppt/`

### 2. quick-capture - Obsidian Quick Capture
Frictionless capture and organization system for Obsidian integration. Handles ideas, links, to-dos, daily notes, and knowledge organization with proper tags and categorization.

**Location**: `quick-capture/`

## Installation

To use these skills with Claude Code:

1. Clone this repository to your local machine
2. Copy the skill directories you want to use to your Claude skills directory:
   - macOS/Linux: `~/Library/Application Support/Claude/skills/`
   - Or your custom skills directory

3. Each skill directory should maintain its structure with SKILL.md, references, and assets subdirectories

## Usage

Once installed, Claude will automatically have access to these skills. Simply reference the skill's domain in your conversation:
- "Create a Billtrust presentation about..."
- "Capture this to my Obsidian daily note..."

## Version Control

This repo allows you to:
- Track changes to your skills over time
- Sync skills across multiple machines
- Share skills with team members
- Maintain consistent skill versions

## Contributing

To add a new skill:
1. Create a new directory with a descriptive name
2. Add a SKILL.md file with the skill definition
3. Include any supporting files in `references/` and `assets/` subdirectories
4. Update this README with the new skill information

## License

Skills may have individual licenses. See LICENSE.txt in each skill directory for details.
