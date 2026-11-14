# Exam GH-600 objective map

This map lists Microsoft's published skills measured for **Exam GH-600: Developing in Agentic AI Systems** and the lessons that teach each one. Rate yourself 1 to 5 on every row, then spend your study time on anything below a 4.

> **Source:** [Exam GH-600 study guide](https://learn.microsoft.com/credentials/certifications/resources/study-guides/gh-600). Microsoft's page shows "Last updated on 2026-05-13." When Microsoft revises the study guide, its list wins over this one.

**About the IDs:** the study guide doesn't number its skills. The IDs here count them in the guide's order (domain, then skill group, then skill), so 2.3.4 is the fourth skill in the third group of domain 2. The numbers in the Lessons column are the learning objectives in each lesson README.

## Prepare agent architecture and SDLC processes (15-20%)

### Integrate agents into the software development lifecycle (SDLC)

| ID | Skill | Lessons | Confidence (1-5) |
| --- | --- | --- | --- |
| 1.1.1 | Identify steps for agents to perform | [Lesson 1](../lessons/lesson-01-agent-architecture-sdlc/) (1.1, 1.2) |  |
| 1.1.2 | Identify and mitigate common anti-patterns in agents | [Lesson 1](../lessons/lesson-01-agent-architecture-sdlc/) (1.2) |  |
| 1.1.3 | Define inputs, outputs, and success criteria for agents | [Lesson 1](../lessons/lesson-01-agent-architecture-sdlc/) (1.3) |  |

### Define boundaries between planning, reasoning, and action

| ID | Skill | Lessons | Confidence (1-5) |
| --- | --- | --- | --- |
| 1.2.1 | Configure agent planning to be distinct from agent execution | [Lesson 1](../lessons/lesson-01-agent-architecture-sdlc/) (1.4) |  |
| 1.2.2 | Configure an agent to output a structured plan | [Lesson 1](../lessons/lesson-01-agent-architecture-sdlc/) (1.4, 1.7) |  |
| 1.2.3 | Validate agent plans | [Lesson 1](../lessons/lesson-01-agent-architecture-sdlc/) (1.4) |  |
| 1.2.4 | Prevent agent action until the agent checked and approved | [Lesson 1](../lessons/lesson-01-agent-architecture-sdlc/) (1.5) |  |

### Configure observability and control for autonomous agents

| ID | Skill | Lessons | Confidence (1-5) |
| --- | --- | --- | --- |
| 1.3.1 | Plan and implement the degree of agent autonomy, including guardrails | [Lesson 1](../lessons/lesson-01-agent-architecture-sdlc/) (1.6), [Lesson 8](../lessons/lesson-08-guardrails-accountability/) (8.2) |  |
| 1.3.2 | Configure agent to produce inspectable artifacts within standard development tooling | [Lesson 1](../lessons/lesson-01-agent-architecture-sdlc/) (1.6) |  |
| 1.3.3 | Configure human intervention for autonomous agents without slowing delivery | [Lesson 1](../lessons/lesson-01-agent-architecture-sdlc/) (1.5), [Lesson 8](../lessons/lesson-08-guardrails-accountability/) (8.5) |  |

## Implement tool use and environment interaction (20-25%)

### Select and configure agent tools

| ID | Skill | Lessons | Confidence (1-5) |
| --- | --- | --- | --- |
| 2.1.1 | Identify required tools | [Lesson 3](../lessons/lesson-03-tools-mcp-servers/) (3.1) |  |
| 2.1.2 | Configure agent tools | [Lesson 3](../lessons/lesson-03-tools-mcp-servers/) (3.1) |  |
| 2.1.3 | Configure agent tool permissions | [Lesson 3](../lessons/lesson-03-tools-mcp-servers/) (3.1) |  |

### Configure MCP servers

| ID | Skill | Lessons | Confidence (1-5) |
| --- | --- | --- | --- |
| 2.2.1 | Add an MCP server as a tool to an agent | [Lesson 3](../lessons/lesson-03-tools-mcp-servers/) (3.2) |  |
| 2.2.2 | Configure a GitHub remote MCP server | [Lesson 3](../lessons/lesson-03-tools-mcp-servers/) (3.3) |  |
| 2.2.3 | Configure the MCP registries | [Lesson 3](../lessons/lesson-03-tools-mcp-servers/) (3.4) |  |
| 2.2.4 | Configure MCP allow lists | [Lesson 3](../lessons/lesson-03-tools-mcp-servers/) (3.4) |  |

### Integrate agents within development environments

| ID | Skill | Lessons | Confidence (1-5) |
| --- | --- | --- | --- |
| 2.3.1 | Evaluate the execution context for an agent | [Lesson 4](../lessons/lesson-04-execution-context/) (4.1) |  |
| 2.3.2 | Configure an agent's scope to a specific repository | [Lesson 2](../lessons/lesson-02-repos-branches-actions/) (2.3) |  |
| 2.3.3 | Configure an agent to be invoked in a CI workflow | [Lesson 4](../lessons/lesson-04-execution-context/) (4.2) |  |
| 2.3.4 | Configure an agent to use branch-based scope | [Lesson 2](../lessons/lesson-02-repos-branches-actions/) (2.3), [Lesson 4](../lessons/lesson-04-execution-context/) (4.3) |  |
| 2.3.5 | Enable an agent to perform autonomous actions, including creating branches and pull requests | [Lesson 4](../lessons/lesson-04-execution-context/) (4.3) |  |
| 2.3.6 | Configure an agent to handle environment-specific constraints | [Lesson 4](../lessons/lesson-04-execution-context/) (4.5) |  |

### Operate agents with safe execution paths and robust error handling

| ID | Skill | Lessons | Confidence (1-5) |
| --- | --- | --- | --- |
| 2.4.1 | Implement error handling | [Lesson 4](../lessons/lesson-04-execution-context/) (4.4) |  |
| 2.4.2 | Implement retries | [Lesson 4](../lessons/lesson-04-execution-context/) (4.4) |  |
| 2.4.3 | Implement rollbacks | [Lesson 4](../lessons/lesson-04-execution-context/) (4.4) |  |
| 2.4.4 | Implement escalation paths | [Lesson 4](../lessons/lesson-04-execution-context/) (4.4) |  |
| 2.4.5 | Implement traceability and accountability for agent actions | [Lesson 2](../lessons/lesson-02-repos-branches-actions/) (2.4), [Lesson 8](../lessons/lesson-08-guardrails-accountability/) (8.6) |  |

## Manage memory, state, and execution (10-15%)

### Implement agent memory strategies

| ID | Skill | Lessons | Confidence (1-5) |
| --- | --- | --- | --- |
| 3.1.1 | Choose between short-term, long-term, and external memory | [Lesson 5](../lessons/lesson-05-memory-state/) (5.1, 5.5) |  |
| 3.1.2 | Scope agent memory to task-relevant information | [Lesson 5](../lessons/lesson-05-memory-state/) (5.2) |  |
| 3.1.3 | Define memory expiration, pruning, and reset rules | [Lesson 5](../lessons/lesson-05-memory-state/) (5.6) |  |

### Persist agent state and manage context drift

| ID | Skill | Lessons | Confidence (1-5) |
| --- | --- | --- | --- |
| 3.2.1 | Capture task progress and decisions as durable artifacts | [Lesson 5](../lessons/lesson-05-memory-state/) (5.3) |  |
| 3.2.2 | Resume agent work without repeating steps or diverging from prior decisions | [Lesson 5](../lessons/lesson-05-memory-state/) (5.4) |  |
| 3.2.3 | Detect and correct drift during extended agent execution | [Lesson 5](../lessons/lesson-05-memory-state/) (5.7) |  |

### Ensure continuity of agent memory and state across tools and environments

| ID | Skill | Lessons | Confidence (1-5) |
| --- | --- | --- | --- |
| 3.3.1 | Share agent state | [Lesson 5](../lessons/lesson-05-memory-state/) (5.2) |  |
| 3.3.2 | Prevent conflicting context | [Lesson 5](../lessons/lesson-05-memory-state/) (5.7) |  |
| 3.3.3 | Prevent stale context | [Lesson 5](../lessons/lesson-05-memory-state/) (5.6, 5.7) |  |

## Perform evaluation, error analysis, and tuning (15-20%)

### Define success criteria and evaluation signals for agent tasks

| ID | Skill | Lessons | Confidence (1-5) |
| --- | --- | --- | --- |
| 4.1.1 | Specify expected outcomes and operational constraints for agent tasks | [Lesson 6](../lessons/lesson-06-evaluation-tuning/) (6.1) |  |
| 4.1.2 | Identify qualitative and quantitative evaluation signals to evaluate agents | [Lesson 6](../lessons/lesson-06-evaluation-tuning/) (6.2) |  |
| 4.1.3 | Align evaluation criteria with development intent | [Lesson 6](../lessons/lesson-06-evaluation-tuning/) (6.2) |  |
| 4.1.4 | Generate evaluation signals by using automated scanning tools | [Lesson 6](../lessons/lesson-06-evaluation-tuning/) (6.3) |  |

### Analyze agent failures and identify root causes

| ID | Skill | Lessons | Confidence (1-5) |
| --- | --- | --- | --- |
| 4.2.1 | Identify failures by using logs, plans, traces, outputs, and workflow artifacts | [Lesson 6](../lessons/lesson-06-evaluation-tuning/) (6.4) |  |
| 4.2.2 | Classify root causes, including reasoning errors, tool misuse, and context or environment issues | [Lesson 6](../lessons/lesson-06-evaluation-tuning/) (6.5) |  |

### Tune agent behavior based on evaluation results

| ID | Skill | Lessons | Confidence (1-5) |
| --- | --- | --- | --- |
| 4.3.1 | Revise instructions, workflows, or constraints | [Lesson 6](../lessons/lesson-06-evaluation-tuning/) (6.6) |  |
| 4.3.2 | Refine memory usage | [Lesson 6](../lessons/lesson-06-evaluation-tuning/) (6.6) |  |
| 4.3.3 | Refine tool usage and tool access | [Lesson 6](../lessons/lesson-06-evaluation-tuning/) (6.6) |  |

## Orchestrate multi-agent coordination (15-20%)

### Operate and manage multi-agent workflows

| ID | Skill | Lessons | Confidence (1-5) |
| --- | --- | --- | --- |
| 5.1.1 | Apply an orchestration pattern to coordinate multiple agents | [Lesson 7](../lessons/lesson-07-multi-agent-coordination/) (7.1, 7.2) |  |
| 5.1.2 | Configure agent isolation for parallel execution | [Lesson 7](../lessons/lesson-07-multi-agent-coordination/) (7.3) |  |
| 5.1.3 | Detect and resolve agent conflicts, including overlapping code changes, duplicated effort, and contradictory outputs | [Lesson 7](../lessons/lesson-07-multi-agent-coordination/) (7.5) |  |

### Configure observability for multi-agent behavior by using logs, artifacts, and operational signals

| ID | Skill | Lessons | Confidence (1-5) |
| --- | --- | --- | --- |
| 5.2.1 | Configure multi-agent workflows to produce artifacts suitable for review and audit | [Lesson 7](../lessons/lesson-07-multi-agent-coordination/) (7.4) |  |
| 5.2.2 | Document key decisions, handoffs, and outcomes across agents | [Lesson 7](../lessons/lesson-07-multi-agent-coordination/) (7.4) |  |
| 5.2.3 | Perform post-hoc analysis of multi-agent behavior | [Lesson 7](../lessons/lesson-07-multi-agent-coordination/) (7.4) |  |

### Detect and respond to multi-agent failures and degraded behavior

| ID | Skill | Lessons | Confidence (1-5) |
| --- | --- | --- | --- |
| 5.3.1 | Identify failed, partial, or stalled agent executions | [Lesson 7](../lessons/lesson-07-multi-agent-coordination/) (7.6) |  |
| 5.3.2 | Respond to degraded behavior or coordination across agents | [Lesson 7](../lessons/lesson-07-multi-agent-coordination/) (7.6, 7.7) |  |
| 5.3.3 | Implement multi-agent recovery patterns, including rollback and human-in-the-loop | [Lesson 7](../lessons/lesson-07-multi-agent-coordination/) (7.7) |  |

### Manage the lifecycle of agents within multi-agent workflows

| ID | Skill | Lessons | Confidence (1-5) |
| --- | --- | --- | --- |
| 5.4.1 | Add agents to existing multi-agent workflows | [Lesson 7](../lessons/lesson-07-multi-agent-coordination/) (7.8) |  |
| 5.4.2 | Update, reconfigure, or replace agents without disrupting active workflows | [Lesson 7](../lessons/lesson-07-multi-agent-coordination/) (7.8) |  |
| 5.4.3 | Retire agents while preserving auditability and workflow continuity | [Lesson 7](../lessons/lesson-07-multi-agent-coordination/) (7.8) |  |

## Implement guardrails and accountability (10-15%)

### Define autonomy levels

| ID | Skill | Lessons | Confidence (1-5) |
| --- | --- | --- | --- |
| 6.1.1 | Classify agent actions by operational, security, and compliance risk to right-size human interventions | [Lesson 8](../lessons/lesson-08-guardrails-accountability/) (8.1) |  |
| 6.1.2 | Assign autonomy levels to maximize delivery speed while remaining compliant with organizational security and Responsible AI standards | [Lesson 8](../lessons/lesson-08-guardrails-accountability/) (8.2) |  |

### Implement guardrails and human-in-the-loop workflows

| ID | Skill | Lessons | Confidence (1-5) |
| --- | --- | --- | --- |
| 6.2.1 | Identify the subset of actions that require human judgment | [Lesson 8](../lessons/lesson-08-guardrails-accountability/) (8.2) |  |
| 6.2.2 | Block actions that violate defined security, compliance, or Responsible AI policies | [Lesson 2](../lessons/lesson-02-repos-branches-actions/) (2.2), [Lesson 8](../lessons/lesson-08-guardrails-accountability/) (8.4) |  |
| 6.2.3 | Scope permissions and execution contexts to enforce least-privilege access | [Lesson 8](../lessons/lesson-08-guardrails-accountability/) (8.3, 8.7) |  |
| 6.2.4 | Require explicit authorization or controlled paths for irreversible or compliance-sensitive changes | [Lesson 2](../lessons/lesson-02-repos-branches-actions/) (2.1), [Lesson 8](../lessons/lesson-08-guardrails-accountability/) (8.5) |  |
| 6.2.5 | Preserve execution velocity by minimizing approvals that do not materially reduce risk | [Lesson 8](../lessons/lesson-08-guardrails-accountability/) (8.5) |  |

## Exam readiness

[Lesson 9](../lessons/lesson-09-exam-readiness/) maps to no single skill. It turns your ratings on this page into a review plan and works a practice scenario from each domain.

[Course README](../README.md)
