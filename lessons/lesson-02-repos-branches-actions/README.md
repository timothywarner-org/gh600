# Lesson 2: Integrate Agents with Repositories, Branches, and Actions

**Exam GH-600 domain:** Implement tool use and environment interaction (20-25%) and Implement guardrails and accountability (10-15%)

## Learning objectives

Each objective is word for word from the course outline. Under it are the study guide skills it serves, with the IDs from the [exam objective map](../../docs/exam-objectives.md).

- 2.1 Apply PR-based governance with templates, required reviews, and CODEOWNERS
  - Skill 6.2.4: Require explicit authorization or controlled paths for irreversible or compliance-sensitive changes
- 2.2 Configure branch protection rules and rulesets as agent guardrails
  - Skill 6.2.2: Block actions that violate defined security, compliance, or Responsible AI policies
- 2.3 Scope agent execution to a repository, branch, or workflow
  - Skill 2.3.2: Configure an agent's scope to a specific repository
  - Skill 2.3.4: Configure an agent to use branch-based scope
- 2.4 Preserve traceability and accountability across agent actions with PR and workflow artifacts
  - Skill 2.4.5: Implement traceability and accountability for agent actions

## Study guide skill groups

- Integrate agents within development environments
- Operate agents with safe execution paths and robust error handling
- Implement guardrails and human-in-the-loop workflows

## Hands-on practice

Lab files for this lesson arrive when the lesson publishes. Its [`demos/`](demos/) page will list them in run order, and the files will live in [`lab/`](../../lab/). Do the [one-time lab setup](../../lab/README.md) now, so you're ready when they land.

Copilot agents rarely produce the same wording twice, so your results will read differently from the video. Look for the same outcome: the plan, the branch, the pull request, the blocked action, or the log entry.

## Before you start

- The accounts and tools in the [one-time lab setup](../../lab/README.md).
- A practice repository you administer, inside your sandbox organization.
- Rulesets and branch protection are available in public repositories on GitHub Free and GitHub Free for organizations, and in private repositories on GitHub Pro, GitHub Team, and GitHub Enterprise Cloud (GitHub Docs, checked November 14, 2026). On a free organization, keep the practice repository public.

## Go deeper

- [Creating a pull request template for your repository](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/creating-a-pull-request-template-for-your-repository)
- [About code owners](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners)
- [About protected branches](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-protected-branches/about-protected-branches)
- [About rulesets](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-rulesets/about-rulesets)
- [Exam GH-600 study guide](https://learn.microsoft.com/credentials/certifications/resources/study-guides/gh-600)
- [Curated links for this course](../../docs/resources.md)

[Course README](../../README.md) | [Exam objective map](../../docs/exam-objectives.md)
