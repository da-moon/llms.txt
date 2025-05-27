# GitLab Documentation Windsurf Workspace Rule

For ANY question about GitLab (repositories, CI/CD, pipelines, jobs, configurations, administration, API, security, etc.), use the gitlab-docs-mcp server to help answer:

- call list_doc_sources tool to get the available llms.txt files
- call fetch_docs tool to read the relevant documentation
- reflect on the URLs in the llms.txt files
- reflect on the input question to determine which documentation sections are most relevant
- call fetch_docs on any URLs relevant to the question
- provide specific examples and code snippets from the documentation when appropriate
- use this documentation to answer the question accurately with GitLab best practices

## GitLab Component Mapping

When questions relate to specific GitLab components, consult these documentation sources:

- For administration questions: GitLabAdmin
- For API usage: GitLabAPI
- For architecture details: GitLabArchitecture
- For CI/CD pipelines, jobs, and .gitlab-ci.yml: GitLabCI
- For cloud seed functionality: GitLabCloudSeed
- For downgrade procedures: GitLabDowngrade
- For drawer components: GitLabDrawers
- For editor extensions: GitLabEditorExtensions
- For installation procedures: GitLabInstall
- For integrations with other tools: GitLabIntegration
- For operations management: GitLabOperations
- For policy information: GitLabPolicy
- For rake tasks: GitLabRaketasks
- For security practices: GitLabSecurity
- For solution implementations: GitLabSolutions
- For subscription management: GitLabSubscriptions
- For general topics: GitLabTopics
- For tutorials: GitLabTutorials
- For update procedures: GitLabUpdate
- For user guides: GitLabUser

Always prioritize official GitLab documentation over other sources when providing answers.
