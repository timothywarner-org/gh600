# Exam GH-600: GitHub Certified Agentic AI Developer (Video)

[![Study guide checked](https://img.shields.io/badge/study%20guide-checked%202026--11--14-0078D4?style=for-the-badge)](https://learn.microsoft.com/credentials/certifications/resources/study-guides/gh-600)
[![License: MIT](https://img.shields.io/badge/license-MIT-2EA44F?style=for-the-badge)](LICENSE)
[![Website](https://img.shields.io/badge/website-TechTrainerTim.com-24292F?style=for-the-badge)](https://techtrainertim.com)
[![GitHub](https://img.shields.io/badge/GitHub-timothywarner--org-24292F?style=for-the-badge&logo=github)](https://github.com/timothywarner-org)

Tim Warner | Pearson video course, Microsoft Press imprint | Companion repository

**Put GitHub Copilot agents to work inside a real software lifecycle, keep them behind guardrails you can prove, and walk into Exam GH-600 knowing why each control exists.**

How do you keep an agent's changes behind a required review? What should an agent remember between sessions, and when should that memory expire? When two agents change the same code, how do you catch it and recover? This course answers those questions with working demos, and this repository is where you practice them.

**Watching the videos?** Open the lesson folder that matches the lesson you're on. Each folder lists the lesson's learning objectives, word for word from the course outline, and the study guide skills each objective serves.

**Studying without the videos?** Start with the [exam objective map](docs/exam-objectives.md). Rate yourself on every skill, then spend your time on anything below a 4.

**Want the lab files?** They arrive lesson by lesson, as each lesson publishes. [`lab/README.md`](lab/README.md) lists the accounts and tools you can set up today, and the [changelog](CHANGELOG.md) tracks every change.

## Course outline

| Lesson | Title | Study guide domain |
| --- | --- | --- |
| 1 | [Prepare Agent Architecture and SDLC Processes](lessons/lesson-01-agent-architecture-sdlc/) | Prepare agent architecture and SDLC processes |
| 2 | [Integrate Agents with Repositories, Branches, and Actions](lessons/lesson-02-repos-branches-actions/) | Implement tool use and environment interaction<br>Implement guardrails and accountability |
| 3 | [Tool Use Part 1 - Configure Agent Tools and MCP Servers](lessons/lesson-03-tools-mcp-servers/) | Implement tool use and environment interaction |
| 4 | [Tool Use Part 2 - Execution Context and Safe Execution Paths](lessons/lesson-04-execution-context/) | Implement tool use and environment interaction |
| 5 | [Manage Memory, State, and Execution](lessons/lesson-05-memory-state/) | Manage memory, state, and execution |
| 6 | [Perform Evaluation, Error Analysis, and Tuning](lessons/lesson-06-evaluation-tuning/) | Perform evaluation, error analysis, and tuning |
| 7 | [Orchestrate Multi-Agent Coordination](lessons/lesson-07-multi-agent-coordination/) | Orchestrate multi-agent coordination |
| 8 | [Implement Guardrails and Accountability](lessons/lesson-08-guardrails-accountability/) | Implement guardrails and accountability |
| 9 | [Exam Readiness and Practice Walkthrough](lessons/lesson-09-exam-readiness/) | Every domain (exam readiness) |

The [exam objective map](docs/exam-objectives.md) goes one level deeper and ties every skill in the study guide to the learning objectives that teach it.

## Exam at a glance

| Item | Detail |
| --- | --- |
| Exam | GH-600: Developing in Agentic AI Systems |
| Certification | GitHub Certified: Agentic AI Developer |
| Who runs it | GitHub maintains the exam, and Microsoft delivers it |
| Passing score | 700 |
| Official study guide | [Exam GH-600 study guide](https://learn.microsoft.com/credentials/certifications/resources/study-guides/gh-600) (Microsoft's page shows "Last updated on 2026-05-13") |
| Certification page | [GitHub Certified: Agentic AI Developer](https://learn.microsoft.com/credentials/certifications/agentic-ai-developer/) |
| Free practice assessment | None listed on the certification page (checked November 14, 2026). Check that page for updates. |

For exam length, question formats, and the exam interface, Microsoft's [exam duration and exam experience](https://learn.microsoft.com/credentials/support/exam-duration-exam-experience) page is the authority.

### Skills measured

| Domain | Weight | Lessons |
| --- | --- | --- |
| Prepare agent architecture and SDLC processes | 15-20% | 1, 8 |
| Implement tool use and environment interaction | 20-25% | 2, 3, 4, 8 |
| Manage memory, state, and execution | 10-15% | 5 |
| Perform evaluation, error analysis, and tuning | 15-20% | 6 |
| Orchestrate multi-agent coordination | 15-20% | 7 |
| Implement guardrails and accountability | 10-15% | 2, 8 |

Lesson 8 shows up in three domains because its autonomy levels and approval paths also serve the first domain, and its signed commits and session logs serve traceability in the second. Lesson 2 shows up twice because pull request governance and rulesets are guardrails in the last domain.

## How the hands-on work runs

Most demos happen on GitHub.com and in Visual Studio Code, because that's where agents do their work. When a demo uses a file, such as a custom agent profile, a workflow, an MCP configuration, or Copilot SDK code, the lesson explains what the file reads and what it changes before it runs. That file lands in this repository when the lesson publishes, with your own organization, repository, and account behind placeholders.

Copilot agents rarely produce the same wording twice, so your results will read differently from the video. Look for the same outcome: the plan, the branch, the pull request, the blocked action, or the log entry.

Do the labs in a GitHub organization kept apart from your real work. Several lessons change organization policy for Copilot, and those settings apply to everyone in that organization.

Copilot cloud agent sessions use GitHub Actions compute and your Copilot plan's usage allowance. Set a budget before you start.

## Before you start

- A **GitHub account**.
- A **paid GitHub Copilot plan**. Copilot cloud agent is available on all paid Copilot plans. On Copilot Business and Copilot Enterprise, an administrator turns it on first.
- A **GitHub organization you own**, for the lessons that set organization policy.
- **Git**, **Visual Studio Code** with GitHub Copilot, and **GitHub CLI**. The [lab setup](lab/README.md) has the links and the checks.
- Working knowledge of Git, pull requests, and GitHub Actions workflows.

## How to study

Every study week, touch each of these:

1. **Theory**: the video course, Microsoft Learn, GitHub Docs, and the official study guide.
2. **Hands-on experience**: your own sandbox organization and the lab files in this repository.
3. **Practice questions**: questions with a full review of every miss. The certification page listed no free practice assessment for GH-600 when this page was checked, so watch that page.

The [study plan template](docs/study-plan-template.md) lays out 30-, 60-, and 90-day schedules.

## What is in this repository

- [`lessons/`](lessons/): one folder per lesson, each with a README and a `demos/` page that will list its lab files
- [`lab/`](lab/): the lab files, lesson by lesson as each lesson publishes, plus the one-time setup
- [`docs/exam-objectives.md`](docs/exam-objectives.md): every study guide skill mapped to a lesson, with a self-rating column
- [`docs/study-plan-template.md`](docs/study-plan-template.md): 30-, 60-, and 90-day schedules
- [`docs/resources.md`](docs/resources.md): curated GitHub Docs and Microsoft Learn links by exam domain
- [`demos/`](demos/): demo material that spans more than one lesson
- [`CHANGELOG.md`](CHANGELOG.md): what changed and when
- [`CONTRIBUTING.md`](CONTRIBUTING.md): how to report a problem or send a fix
- [`NOTICE.md`](NOTICE.md) and [`LICENSE`](LICENSE): license, publisher, and trademark notices

## About the author

**Tim Warner** is a Microsoft MVP, a Microsoft Certified Trainer since 1997, and a Principal Staff Author at Pluralsight with more than 200 courses and over a million learners. He teaches live courses for Pearson and O'Reilly, and he builds and ships MCP servers. His teaching model comes from Richard Feynman: start from first principles, prove the idea with a working demo, and keep the examples close to real enterprise work.

You can find his video courses on [Pluralsight](https://www.pluralsight.com/authors/tim-warner), short tutorials on [YouTube](https://www.youtube.com/@TechTrainerTim), more course repositories on [GitHub](https://github.com/timothywarner-org), and everything else at [TechTrainerTim.com](https://techtrainertim.com). Connect with him on [LinkedIn](https://www.linkedin.com/in/timothywarner).

## Acknowledgments

- **Microsoft Press** and **Pearson** for publishing this title
- **Laura Lewin** for steering it
- The GitHub Copilot, GitHub Actions, and GitHub Advanced Security teams for shipping the products this exam tests
- Every certification candidate who asked the question that made this material better

## License

The code and documentation in this repository are released under the [MIT License](LICENSE). The course videos and Pearson materials are licensed separately by Pearson. See [NOTICE.md](NOTICE.md) for publisher and trademark notices.

*Go earn that badge.*
