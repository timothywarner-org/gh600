# Lesson 8: Implement Guardrails and Accountability

**Exam GH-600 domain:** Implement guardrails and accountability (10-15%)  
**Also serves skills from:** Prepare agent architecture and SDLC processes (1.3.1, 1.3.3), Implement tool use and environment interaction (2.4.5)

## Learning objectives

Each objective is word for word from the course outline. Under it are the study guide skills it serves, with the IDs from the [exam objective map](../../docs/exam-objectives.md).

- 8.1 Classify agent actions by operational, security, and compliance risk
  - Skill 6.1.1: Classify agent actions by operational, security, and compliance risk to right-size human interventions
- 8.2 Assign autonomy levels and identify actions requiring human judgment under Responsible AI standards
  - Skill 1.3.1: Plan and implement the degree of agent autonomy, including guardrails
  - Skill 6.1.2: Assign autonomy levels to maximize delivery speed while remaining compliant with organizational security and Responsible AI standards
  - Skill 6.2.1: Identify the subset of actions that require human judgment
- 8.3 Scope permissions and enforce least-privilege GITHUB_TOKEN defaults
  - Skill 6.2.3: Scope permissions and execution contexts to enforce least-privilege access
- 8.4 Block policy-violating actions with firewall controls, workflow approval policies, and rulesets
  - Skill 6.2.2: Block actions that violate defined security, compliance, or Responsible AI policies
- 8.5 Require explicit authorization or controlled paths for irreversible or compliance-sensitive actions; minimize approvals that do not reduce risk
  - Skill 1.3.3: Configure human intervention for autonomous agents without slowing delivery
  - Skill 6.2.4: Require explicit authorization or controlled paths for irreversible or compliance-sensitive changes
  - Skill 6.2.5: Preserve execution velocity by minimizing approvals that do not materially reduce risk
- 8.6 Audit agent activity with signed commits, session logs, and co-authorship attribution
  - Skill 2.4.5: Implement traceability and accountability for agent actions
- 8.7 Verify current protection boundaries across Copilot surfaces, content exclusions, MCP servers, and setup steps
  - Skill 6.2.3: Scope permissions and execution contexts to enforce least-privilege access

## Study guide skill groups

- Configure observability and control for autonomous agents
- Operate agents with safe execution paths and robust error handling
- Define autonomy levels
- Implement guardrails and human-in-the-loop workflows

## Hands-on practice

Lab files for this lesson arrive when the lesson publishes. Its [`demos/`](demos/) page will list them in run order, and the files will live in [`lab/`](../../lab/). Do the [one-time lab setup](../../lab/README.md) now, so you're ready when they land.

Copilot agents rarely produce the same wording twice, so your results will read differently from the video. Look for the same outcome: the plan, the branch, the pull request, the blocked action, or the log entry.

## Before you start

- The accounts and tools in the [one-time lab setup](../../lab/README.md).
- A practice organization and repository you administer, kept apart from your real work, because this lesson changes token permissions, rulesets, and Copilot settings.

## Go deeper

- [Authenticate with GITHUB_TOKEN](https://docs.github.com/en/actions/tutorials/authenticate-with-github_token)
- [Build guardrails for Copilot cloud agent](https://docs.github.com/en/copilot/tutorials/cloud-agent/build-guardrails)
- [Risks and mitigations for Copilot cloud agent](https://docs.github.com/en/copilot/concepts/security-governance-and-network-settings/risks-and-mitigations)
- [About rulesets](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-rulesets/about-rulesets)
- [About commit signature verification](https://docs.github.com/en/authentication/managing-commit-signature-verification/about-commit-signature-verification)
- [Content exclusion for GitHub Copilot](https://docs.github.com/en/copilot/concepts/security-governance-and-network-settings/content-exclusion)
- [Customizing or disabling the firewall for GitHub Copilot](https://docs.github.com/en/copilot/how-tos/copilot-on-github/customize-copilot/customize-the-firewall)
- [Exam GH-600 study guide](https://learn.microsoft.com/credentials/certifications/resources/study-guides/gh-600)
- [Curated links for this course](../../docs/resources.md)

[Course README](../../README.md) | [Exam objective map](../../docs/exam-objectives.md)
