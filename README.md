# Easy Skills Packages

Official Skills repository for [Easy Skills CLI](https://github.com/easy-skills/easy-skills).

This repository hosts the official collection of AI skills available for installation via the `easy-skills` command-line tool.

## Directory Structure

- **packages/**: Contains all skill definitions (`.skill` files), organized by category.
- **skills-registry.json**: The central registry file mapping skill names to their locations.

## Usage

These skills are automatically available when using the Easy Skills CLI with the default configuration (`official` registry).

```bash
# List available skills
easy-skills list

# Install a skill
easy-skills install patent-writer
```

## Contributing

Contributions are welcome! If you have a useful skill to share or want to improve an existing one, please submit a Pull Request.

1. Fork this repository.
2. Create your skill in the `packages/` directory.
3. Update `skills-registry.json` to include your new skill.
4. Submit a PR.

---
License: MIT