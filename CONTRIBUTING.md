# Contributing Guide

Thank you for your interest in contributing! This guide explains how to add resources to this repository.

## For Non-Technical Contributors

You don't need to know Git to contribute. Just use our issue templates:

1. Go to [Issues](../../issues)
2. Click **New Issue**
3. Select a template:
   - **Submit a Prompt** - For sharing prompt text
   - **Submit a Tool or Resource** - For adding links to the CSV
   - **General Suggestion** - For anything else
4. Fill out the form
5. Click Submit

A maintainer will review your submission and add it to the repository.

## For Technical Contributors

### Adding a Prompt

1. Fork this repository
2. Create a new `.md` or `.txt` file in `/prompts/`
3. Use a descriptive filename (e.g., `reflective-dialogue.md`)
4. Submit a Pull Request

### Adding to the Resources CSV

1. Fork this repository
2. Edit `resources.csv`
3. Add a new row with these columns:
   - `name` - Resource name
   - `type` - One of: prompt, tool, mcp-server, platform, article, other
   - `description` - Brief description
   - `url` - Link to the resource
   - `contributor` - Your name/handle (optional)
   - `date_added` - Today's date (YYYY-MM-DD)
4. Submit a Pull Request

### Adding Tool/MCP Documentation

1. Fork this repository
2. Create a new `.md` file in `/tools/` or `/mcp-servers/`
3. Include relevant details (see folder READMEs for guidance)
4. Submit a Pull Request

## License

All contributions are released into the public domain under CC0 1.0. By contributing, you agree to this.

## Questions?

Open a [General Suggestion](../../issues/new?template=general-suggestion.yml) issue!
