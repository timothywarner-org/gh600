# Lesson 1: Prepare Agent Architecture and SDLC Processes

**Exam GH-600 domain:** Prepare agent architecture and SDLC processes (15-20%)

## Learning objectives

Each objective is word for word from the course outline. Under it are the study guide skills it serves, with the IDs from the [exam objective map](../../docs/exam-objectives.md).

- 1.1 Distinguish agents from assistants and apply the plan-act-evaluate lifecycle
  - Skill 1.1.1: Identify steps for agents to perform
- 1.2 Identify suitable agent tasks and mitigate common agent anti-patterns
  - Skill 1.1.1: Identify steps for agents to perform
  - Skill 1.1.2: Identify and mitigate common anti-patterns in agents
- 1.3 Define inputs, outputs, constraints, and success criteria as a structured-task contract
  - Skill 1.1.3: Define inputs, outputs, and success criteria for agents
- 1.4 Separate planning, reasoning, and action; generate and validate structured plans
  - Skill 1.2.1: Configure agent planning to be distinct from agent execution
  - Skill 1.2.2: Configure an agent to output a structured plan
  - Skill 1.2.3: Validate agent plans
- 1.5 Gate execution until plans are checked and approved; define human-intervention points
  - Skill 1.2.4: Prevent agent action until the agent checked and approved
  - Skill 1.3.3: Configure human intervention for autonomous agents without slowing delivery
- 1.6 Apply the contributor model to review inspectable agent artifacts and calibrate autonomy
  - Skill 1.3.1: Plan and implement the degree of agent autonomy, including guardrails
  - Skill 1.3.2: Configure agent to produce inspectable artifacts within standard development tooling
- 1.7 Build an implementation-planner custom agent with organization-level .github-private setup
  - Skill 1.2.2: Configure an agent to output a structured plan

## Study guide skill groups

- Integrate agents into the software development lifecycle (SDLC)
- Define boundaries between planning, reasoning, and action
- Configure observability and control for autonomous agents

## Hands-on practice

Lab files for this lesson arrive when the lesson publishes. Its [`demos/`](demos/) page will list them in run order, and the files will live in [`lab/`](../../lab/). Do the [one-time lab setup](../../lab/README.md) now, so you're ready when they land.

Copilot agents rarely produce the same wording twice, so your results will read differently from the video. Look for the same outcome: the plan, the branch, the pull request, the blocked action, or the log entry.

## Before you start

- The accounts and tools in the [one-time lab setup](../../lab/README.md).
- A GitHub organization you own, for objective 1.7. Organization custom agent profiles live in the `/agents` folder of the organization's `.github` or `.github-private` repository, and GitHub Docs recommends `.github-private`, set to private.
- Custom agents are in public preview, so expect screens and options to change (GitHub Docs, checked November 14, 2026).

## Go deeper

- [Preparing to use custom agents in your organization](https://docs.github.com/en/copilot/how-tos/administer-copilot/manage-for-organization/prepare-for-custom-agents)
- [Implementation planner custom agent tutorial](https://docs.github.com/en/copilot/tutorials/customization-library/custom-agents/implementation-planner)
- [Get started with Copilot agents on GitHub](https://docs.github.com/en/copilot/how-tos/copilot-on-github/use-copilot-agents/overview)
- [Exam GH-600 study guide](https://learn.microsoft.com/credentials/certifications/resources/study-guides/gh-600)
- [Curated links for this course](../../docs/resources.md)

[Course README](../../README.md) | [Exam objective map](../../docs/exam-objectives.md)
