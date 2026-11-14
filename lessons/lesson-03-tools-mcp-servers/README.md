# Lesson 3: Tool Use Part 1 - Configure Agent Tools and MCP Servers

**Exam GH-600 domain:** Implement tool use and environment interaction (20-25%)

## Learning objectives

Each objective is word for word from the course outline. Under it are the study guide skills it serves, with the IDs from the [exam objective map](../../docs/exam-objectives.md).

- 3.1 Select and scope agent tools using least privilege; implement tool restrictions with the Copilot SDK
  - Skill 2.1.1: Identify required tools
  - Skill 2.1.2: Configure agent tools
  - Skill 2.1.3: Configure agent tool permissions
- 3.2 Register and configure MCP servers as agent tools
  - Skill 2.2.1: Add an MCP server as a tool to an agent
- 3.3 Configure the GitHub remote MCP server end to end
  - Skill 2.2.2: Configure a GitHub remote MCP server
- 3.4 Configure MCP registries and enforce MCP allow-lists
  - Skill 2.2.3: Configure the MCP registries
  - Skill 2.2.4: Configure MCP allow lists

## Study guide skill groups

- Select and configure agent tools
- Configure MCP servers

## Hands-on practice

Lab files for this lesson arrive when the lesson publishes. Its [`demos/`](demos/) page will list them in run order, and the files will live in [`lab/`](../../lab/). Do the [one-time lab setup](../../lab/README.md) now, so you're ready when they land.

Copilot agents rarely produce the same wording twice, so your results will read differently from the video. Look for the same outcome: the plan, the branch, the pull request, the blocked action, or the log entry.

## Before you start

- The accounts and tools in the [one-time lab setup](../../lab/README.md).
- Objective 3.4 sets MCP registry and allow-list policy. GitHub Docs lists that for organization and enterprise owners on Copilot Business or Copilot Enterprise, and restricting MCP access to a custom registry is in public preview (checked November 14, 2026).
- Keep personal access tokens out of every file. When an MCP server needs a token, use a fine-grained token with the least access the task needs.

## Go deeper

- [Custom agents and sub-agent orchestration in the Copilot SDK](https://docs.github.com/en/copilot/how-tos/copilot-sdk/features/custom-agents)
- [Set up the GitHub MCP server](https://docs.github.com/en/copilot/how-tos/copilot-in-your-ide/customize-copilot/extend-copilot-with-tools-and-context/set-up-the-github-mcp-server)
- [MCP servers for Copilot cloud agent](https://docs.github.com/en/copilot/how-tos/copilot-on-github/customize-copilot/configure-mcp-servers)
- [Restrict MCP server access to a custom registry](https://docs.github.com/en/copilot/how-tos/administer-copilot/manage-mcp-usage/restrict-based-on-registry)
- [Exam GH-600 study guide](https://learn.microsoft.com/credentials/certifications/resources/study-guides/gh-600)
- [Curated links for this course](../../docs/resources.md)

[Course README](../../README.md) | [Exam objective map](../../docs/exam-objectives.md)
