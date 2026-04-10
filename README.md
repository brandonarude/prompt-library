# Prompt Library

A personal collection of reusable prompts, organized by category and tagged by model compatibility.

## Categories

| Category | Description |
|---|---|
| [coding](prompts/coding/) | Code review, refactoring, debugging, and development prompts |
| [writing](prompts/writing/) | Content creation, editing, and copywriting prompts |
| [analysis](prompts/analysis/) | Data analysis, research, and reasoning prompts |
| [meeting-summary](prompts/meeting-summary/) | Meeting notes, summaries, and action item extraction |
| [general](prompts/general/) | General-purpose prompts that span multiple use cases |

## Usage

Each prompt is a markdown file with YAML frontmatter containing metadata:

- **title** — Name of the prompt
- **category** — Which folder it belongs to
- **models** — Which models the prompt is optimized for
- **tags** — Searchable keywords
- **created** — Date the prompt was added

See [TEMPLATE.md](prompts/TEMPLATE.md) for the format to follow when adding new prompts.

## Adding a Prompt

1. Copy `prompts/TEMPLATE.md` into the appropriate category folder
2. Rename the file to something descriptive (e.g., `code-review.md`)
3. Fill in the frontmatter and content
4. Update this README if adding a new category
