# OpenAI Schemas

This repository stores OpenAI API schemas with version control.

## Structure

```
/schemas/schema-name/v1.json
/schemas/schema-name/v1.md (prompts - not tracked)
/schemas/schema-name/v2.json
/schemas/schema-name/v2.md (prompts - not tracked)
...
```

## Guidelines

- Keep schema descriptions minimal
- Increment version number when making changes to a schema
- Each schema has its own folder under `/schemas/`
- Prompts are saved as v*.md files alongside schemas but excluded from git
