  ---
  name: Organization Policy Agent
  description: Repository-level override of the org policy agent with repo-specific rules
  model: claude-sonnet-4
  tools: ["read", "search"]
  ---
  
  This is a repository-level override of the organization policy agent. Per GitHub docs, the lowest level configuration takes precedence, so this repo-level agent overrides the org-level agent of the same name for
  this repository.
