# Learn Python for AI - Documentation Project

## Project Overview
This is a comprehensive beginner course for learning Python specifically for AI development. The course teaches Python foundations that students need to confidently work with Python in AI applications.

## Project Setup
- **Course Name**: Learn Python for AI
- **Domain**: python.datalumina.com
- **Author**: Dave Ebbelaar
- **Company**: Datalumina

## Navigation Structure
The course uses a progressive horizontal tab structure:
1. **Introduction** - Course welcome, why Python, AI assistants
2. **Getting Started** - Python setup and developer tools
3. **Python Basics** - Variables, data types, operators, control flow, data structures
4. **Building Programs** - Functions, external tools, classes, error handling
5. **Tools** - Git, GitHub, environment variables, modern Python with uv
6. **Next Steps** - Course summary, feedback, AI agents follow-up course

## Style Guide

### Capitalization Patterns
**Navigation & Menu Items**
- Tab names: Title case (e.g., "Introduction", "Getting Started")
- Page titles: Sentence case (e.g., "Course welcome", "Why Python")
- Card titles: Sentence case (e.g., "Complete beginner", "AI focused")
- Navigation cards: Sentence case (e.g., "Begin the course", "Setup Python")

**Headers**
- H1: Not used (page title in frontmatter)
- H2: Sentence case for all section headers (e.g., "Complete beginner course", "Learning with AI assistants")
- H3+: Sentence case throughout

**Cards**
- Card titles: Sentence case
- Card descriptions: Sentence case, no ending punctuation unless multiple sentences

**Technical Terms**
- Product names: Always capitalize (Python, Claude, OpenAI)
- Model names: Title case with versions (Claude 4 Sonnet)
- Features/concepts: Lowercase unless proper nouns

### Tone of Voice
- **Perspective**: Second-person ("you") for direct communication
- **Style**: Concise and direct, no fluff or preamble
- **Length**: Keep sections short - 2-3 sentences per paragraph
- **Focus**: Python foundations for AI, not building actual AI applications
- **Examples**: "Learn Python from scratch" not "Build AI applications"

### Content Structure Patterns

**Key Principles**
- Brevity is essential - get to the point quickly
- No lengthy introductions or conclusions
- Combine short sections into cohesive ones

**Paragraphs**
- Maximum 2-3 sentences per paragraph
- One main idea per paragraph
- No verbose explanations

**Cards (CardGroup)**
- Use 2-3 columns for feature highlights
- Navigation cards: 2 columns max
- No color attributes on cards - use default styling
- Include href links for all tool mentions
- Keep descriptions to one line when possible

**Bullet Points**
- Prerequisites or requirements
- Quick feature lists
- Step-by-step instructions (numbered for sequences)
- Key takeaways or summaries

**Code Blocks**
- Always include language tag
- Add filename/context comment when helpful
- Test all examples before publishing
- Keep examples focused and minimal

**Notes/Tips/Warnings**
- `<Note>` for important context
- `<Tip>` for best practices
- `<Warning>` for potential issues
- Use sparingly for emphasis

### Title Guidelines
- All page titles use 2-3 words in sentence case
- Group names use sentence case
- Keep titles short and clear for visual consistency
- All pages include FontAwesome icons in frontmatter

## Course Content Structure
```
docs/
├── index.mdx                    # Main landing page
├── introduction/                # Welcome and motivation
├── getting-started/             # Environment setup
├── basics/                      # Basic Python concepts
├── data-types/                  # Numbers, strings, booleans
├── control-flow/                # Program logic
├── data-structures/             # Lists, dicts, tuples, sets
├── functions/                   # Reusable code
├── libraries-apis/              # External tools
├── practical-python/            # Project structure, files
├── advanced/                    # Error handling, classes
├── tools/                       # Git, environment, dependencies
└── next-steps/                  # Summary, feedback, AI agents
```

## Mintlify Configuration
- Format: MDX files with YAML frontmatter
- Config: docs.json for navigation, theme, settings
- Components: Mintlify components (Card, CardGroup, Note, Tip, etc.)

## Content Strategy
- Keep content concise - aim for brevity without sacrificing clarity
- Each section should be 2-3 paragraphs maximum
- Focus on Python foundations, not building actual AI applications
- Prioritize practical learning over theory
- Check existing patterns for consistency
- When mentioning tools, always include working links

## Frontmatter Requirements
- title: 2-3 words in sentence case
- description: Concise summary for SEO/navigation

## Writing Standards
- Second-person voice ("you")
- Prerequisites at start of procedural content
- Test all code examples before publishing
- Match style and formatting of existing pages
- Include both basic and advanced use cases
- Language tags on all code blocks
- Alt text on all images
- Relative paths for internal links

## Git Workflow
- NEVER use --no-verify when committing
- Ask how to handle uncommitted changes before starting
- Create a new branch when no clear branch exists for changes
- Commit frequently throughout development
- NEVER skip or disable pre-commit hooks

## Do Not
- Skip frontmatter on any MDX file
- Use absolute URLs for internal links
- Include untested code examples
- Make assumptions - always ask for clarification
- Use more than 3 words in titles
- Add color codes to cards (e.g., color="#3455ee")
- Use emojis in content
- Create lengthy explanations - be concise
- Use Title Case for headers or card titles (use sentence case)

## Markdown and Formatting Tips
- You don't need to use `<br>` in accordings when it follows a code block or bullet list. Only use `<br>` with an explanation and then a code block or list.

## Project Memories
- All arrows use this icon: > (should be standard for arrow icon in project)
- NEVER use text pattern like "why environment variables matter" as it's a clear Claude giveaway and should be adjusted
- Course completion flow: Tools (complete-setup) > Course Summary > Feedback > AI Agents
- Anaconda is mentioned but not recommended (stick with venv and pip)
- All next-steps files are in /next-steps/ folder (course-summary.mdx, feedback.mdx, ai-agents.mdx)