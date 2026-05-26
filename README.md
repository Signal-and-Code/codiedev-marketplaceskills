# CodieDev Skill Marketplace

Curated skills for the CodieDev Skill Marketplace. The CodieDev portal syncs this repo every 6 hours to populate the marketplace catalog.

## Structure

```
catalog.json          # Manifest with metadata (categories, tags, featured)
skills/
  <slug>/
    SKILL.md          # Standard SKILL.md with name: and description: frontmatter
```

## Adding a skill

1. Create a folder under `skills/` with a kebab-case slug
2. Add a `SKILL.md` with YAML frontmatter (`name:` and `description:` required)
3. Add an entry to `catalog.json` with category, tags, and featured flag
4. Open a PR

## Frontmatter format

```yaml
---
name: my-skill-name
description: What this skill does in one line
---

# Skill content in markdown...
```
