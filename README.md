# llms.txt Collection

This repository contains a collection of llms.txt files, MCP server
configurations, and editor workspace rules for enhanced AI-assisted
development.

## What is llms.txt?

The llms.txt format is a Markdown-based standard designed to help Large
Language Models (LLMs) better understand and process website documentation.
Proposed by Jeremy Howard in September 2024, it provides a structured way to
present information that AI systems can easily parse and utilize.

## Format Specification

### Core Structure

The llms.txt format follows a specific Markdown structure:

```markdown
# Project Name

> Brief project summary

Additional context and important notes

## Core Documentation

- [Resource Name](url): Description of the resource
- [API Reference](url): API documentation details

## Optional

- [Additional Resources](url): Supplementary information
```

### Required Elements

1. **H1 Header**: Project or topic name (only required section)
2. **Blockquote**: Brief summary containing key information
3. **H2 Sections**: Organized documentation links with descriptions
4. **Optional Section**: Secondary resources that can be skipped for shorter
   context

### Two File Types

- **llms.txt**: Index file with navigation links and brief descriptions
- **llms-full.txt**: Comprehensive file containing all documentation content

## Purpose and Benefits

- **Context Window Optimization**: Provides concise, structured information
  within LLM context limits
- **HTML Noise Reduction**: Eliminates navigation elements, JavaScript, CSS,
  and other non-essential content
- **AI-First Documentation**: Designed specifically for AI systems while
  remaining human-readable
- **Standardization**: Creates a consistent format for AI tools to access
  website information

## Repository Contents

### Converted Documentation

- `gitlab/`: Collection of GitLab-related documentation converted to llms.txt
  format
- `typingmind/`: TypingMind-specific llms.txt files
- `cloudcraft/`: Cloudcraft documentation in `llms.txt` format.
- `cosign/`: Cosign documentation in `llms.txt` format.

### MCP Server Configuration

- `mcp.json`: Configuration files for launching mcpdoc MCP server
- `command`: Raw command for launching mcpdoc MCP server
- `rule.md`: Windsurf/Cursor editor workspace rules for MCP server integration

## Usage with AI Tools

### IDE Integration (Cursor, Windsurf)

- Add llms-full.txt as custom documentation
- IDE automatically chunks and indexes content for RAG
- Enables context-aware code completion and assistance

### Chat Models

- Use models with large context windows
- Implement RAG strategy for efficient documentation querying
- Direct file inclusion for immediate context

## Format Guidelines

### Best Practices

- Start with H1 project name
- Include blockquote summary
- Use H2 headers to organize sections
- Provide brief, clear descriptions for each link
- Keep content focused and relevant
- Use "Optional" section for secondary information

### Content Organization

- **Core Documentation**: Essential resources and guides
- **API Reference**: Technical documentation and specifications
- **Tutorials**: Step-by-step guides and examples
- **Optional**: Supplementary materials and advanced topics

## Resources

- [Official llms.txt Specification](https://llmstxt.org/)
- [GitHub Repository](https://github.com/AnswerDotAI/llms-txt)
- [Directory of Adopters](http://directory.llmstxt.cloud)
- [Original Proposal by Answer.AI](https://www.answer.ai/posts/2024-09-03-llmstxt.html)
