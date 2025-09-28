# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a navi cheat sheet repository containing command-line reference files. Navi is an interactive cheatsheet tool for the command-line that allows users to browse through cheatsheets and execute commands directly.

## Repository Structure

- `cheats/` - Contains all cheat sheet files organized by topic:
  - `system.cheat` - System monitoring, process management, and service control
  - `network.cheat` - Network commands, connections, downloads, and SSH
  - `user.cheat` - User management, permissions, and sudo operations
  - `archive.cheat` - File compression and archive operations (tar, zip, etc.)
  - `file.cheat` - File operations, search, statistics, and directory management
  - `docker.cheat` - Docker container and image management commands
  - `git.cheat` - Git commands for log viewing, branch management, reset operations, and file history
  - `conda.cheat` - Conda environment management commands
  - `navi.cheat` - Navi-specific commands for managing repositories

## Cheat Sheet Format

Each `.cheat` file follows navi's syntax:
- `% category, tags` - Defines categories and searchable tags
- `# description` - Human-readable command description
- `command with <placeholder>` - Actual command with variable placeholders
- `$ placeholder: command` - Auto-completion for placeholders using command output

## Common Development Tasks

### Adding New Cheat Sheets
- Create new `.cheat` files in the `cheats/` directory
- Follow the existing naming convention (topic.cheat)
- Use consistent category and tag naming with existing files

### Updating Repository
Use the command from `navi.cheat`:
```bash
navi repo add https://github.com/Rem-yl/cheats
```

## Language and Content
- All cheat sheets are in Chinese with command descriptions
- Focus on practical, frequently-used commands
- Include auto-completion helpers for dynamic values (branches, files, etc.)