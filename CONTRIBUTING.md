# Contributing

Thank you for helping make this course companion better. Fixes are welcome from anyone working through the GH-600 course or preparing for the exam.

## What to submit

**Yes, please:**

- Typos, broken links, and dead GitHub Docs or Microsoft Learn URLs
- Lab steps that no longer match GitHub.com or Visual Studio Code because a product changed
- Clarifications about GitHub Copilot agents, MCP servers, GitHub Actions, or repository rules that you found while studying
- Optional command-line equivalents (GitHub CLI or Git) for a GitHub.com step, clearly labeled as optional
- Practice scenarios that you wrote yourself (see the next section)

**Please don't submit:**

- Verbatim or paraphrased questions from any GH-600 exam. Sharing them breaks the exam agreement you accepted when you sat the exam.
- Promotional content for other courses or products
- Content that doesn't map to a skill in the [exam objective map](docs/exam-objectives.md)

## How to submit

1. **Small fixes** (typos, broken links): open an issue with the *Typo or broken link* template, or send a pull request.
2. **Lab fixes or new content**: open an issue with the *Content question or demo issue* template first, so the change is scoped before you spend time on it.
3. **Larger contributions**: mention [@timothywarner](https://github.com/timothywarner) on the issue before you open a pull request.

## Style

- Lab steps lead with GitHub.com and Visual Studio Code. Command-line steps are optional and say so.
- Every value a learner would change (organization, repository, account) sits behind a placeholder such as `<your-org>`, never hardcoded in a file.
- Workflows set `permissions:` explicitly and grant `GITHUB_TOKEN` only what the job needs.
- A script that changes state says what it reads and what it changes in its help, and stops for a typed confirmation before its first write.
- Every lab ends with cleanup, so learners don't keep paying for leftover settings or usage.
- No secrets, tokens, keys, or real organization data in any file.
- Markdown is GitHub-flavored, plain ASCII, with language hints on code fences.

## Code of conduct

Be kind and assume good faith, and when you disagree, argue with the idea rather than the person. The [Contributor Covenant](https://www.contributor-covenant.org/version/2/1/code_of_conduct/) applies.
