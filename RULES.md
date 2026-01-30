# Project Rules

## Schema Versioning

**CRITICAL RULE: Always increment version numbers when changing schemas. Never edit existing versions.**

When a schema needs to be modified:
1. Create a new version file (e.g., v2.json, v3.json, etc.)
2. Create a corresponding prompt file (e.g., v2.md, v3.md, etc.)
3. Leave previous versions unchanged

## Schema Guidelines

- Keep schema descriptions minimal
- Use clear, concise property names
- Include only required fields in the schema

## Prompt Files

- Prompts are saved as v*.md files alongside JSON schemas
- All v*.md files are excluded from git (never committed)
- Structure prompts with separate system and user sections
