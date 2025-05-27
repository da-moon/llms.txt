## TypingMind Documentation Consultation Rule

For ANY question, task, or development work related to typingmind.com, ALWAYS use the typingmind-docs-mcp server to help answer:

1. Call `list_doc_sources` tool to get the available llms.txt file
2. Call `fetch_docs` tool to read the llms.txt content
3. Carefully analyze the URLs in llms.txt and identify which sections are relevant to the current question
4. Call `fetch_docs` on all URLs relevant to the question or task
5. Thoroughly read and understand the documentation before providing any answers or solutions
6. Reference specific documentation sections in your responses
7. If the documentation doesn't fully address the question, clearly indicate what information is missing

This rule applies to:
- Any questions about TypingMind features or functionality
- Development tasks involving TypingMind integration
- Troubleshooting TypingMind-related issues
- Configuration of TypingMind components
- Any code that interacts with TypingMind APIs or services

When working with Python sandbox packages for TypingMind, ensure you understand the documentation regarding package installation for debugging, particularly focusing on `langchain` and related libraries.
