# Lab files

Lab files arrive lesson by lesson, as each lesson publishes. Nothing in this folder runs yet, so this page covers what the lab will hold and what you can set up today.

## What the lab will hold

- One folder per lesson with the files that lesson's demos use, such as custom agent profiles, repository instructions, pull request templates, workflow files, MCP server configuration, and Copilot SDK code.
- Help at the top of every file that says what it reads and what it changes.
- Placeholders for every value you'd change, such as `<your-org>`, `<your-repo>`, and `<your-github-account>`, so nothing points at the course's own organization.
- Workflows that set `permissions:` explicitly and give `GITHUB_TOKEN` only what each job needs.
- A cleanup section for every lesson that changes organization settings or uses billable time.

Each lesson folder under [`lessons/`](../lessons/) has a `demos/README.md` that will list that lesson's files in run order.

## Set up now

### 1. A GitHub account

Use an account you control. [Creating an account on GitHub](https://docs.github.com/en/account-and-profile/how-tos/account-management/creating-an-account-on-github) walks through it.

### 2. A paid GitHub Copilot plan

Copilot cloud agent, which several lessons use, is available on all paid Copilot plans: Copilot Pro, Copilot Pro+, and Copilot Max for individuals, and Copilot Business and Copilot Enterprise for organizations. Copilot Free doesn't include Copilot in the cloud. On Copilot Business and Copilot Enterprise, an administrator turns on Copilot cloud agent through policy before you can use it.

Sources: [Plans for GitHub Copilot](https://docs.github.com/en/copilot/get-started/plans) and [Managing GitHub Copilot policies as an individual subscriber](https://docs.github.com/en/copilot/how-tos/manage-your-account/manage-policies), checked November 14, 2026.

### 3. A sandbox GitHub organization you own

Keep it apart from your real work, because several lessons change organization policy for Copilot. Lesson 1 adds a custom agent to the organization's `.github-private` repository, and Lesson 3 sets MCP registry and allow-list policy, which GitHub Docs lists for Copilot Business and Copilot Enterprise. [Creating a new organization from scratch](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/creating-a-new-organization-from-scratch) walks through it.

### 4. Public or private practice repositories

On GitHub Free and GitHub Free for organizations, rulesets, branch protection, code scanning, dependency review, and secret scanning are available in public repositories. Private repositories need a paid GitHub plan for rulesets and branch protection, and paid GitHub security products for the scanners. If you choose public, keep every token and secret out of the repository.

Sources: [About rulesets](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-rulesets/about-rulesets) and [About GitHub Advanced Security](https://docs.github.com/en/get-started/learning-about-github/about-github-advanced-security), checked November 14, 2026.

### 5. Git

Install the latest Git from the link in [Set up Git](https://docs.github.com/en/get-started/git-basics/set-up-git), then confirm it runs:

```shell
git --version
```

### 6. Visual Studio Code with GitHub Copilot

Install Visual Studio Code from its [download page](https://code.visualstudio.com/Download), then sign in to GitHub in Visual Studio Code. The Copilot extensions install themselves the first time you set up Copilot, as [About GitHub Copilot in Visual Studio Code](https://docs.github.com/en/copilot/how-tos/copilot-in-your-ide/set-up-copilot/install-copilot-extension) describes. Confirm it runs:

```shell
code --version
```

### 7. GitHub CLI

Install GitHub CLI from the [installation section](https://github.com/cli/cli#installation) of its repository, as the [GitHub CLI quickstart](https://docs.github.com/en/github-cli/github-cli/quickstart) describes. Then sign in and confirm the account:

```shell
gh --version
gh auth login
gh auth status
```

At the `gh auth login` prompts, choose **GitHub.com** and follow the steps on screen. [`gh auth status`](https://cli.github.com/manual/gh_auth_status) shows which account you're signed in as.

## Costs

Copilot cloud agent uses GitHub Actions compute and your Copilot plan's usage allowance for each session (GitHub Docs, checked November 14, 2026). Set a budget for your account or organization before the labs arrive. [GitHub billing documentation](https://docs.github.com/en/billing) covers budgets and spending.

## Fictional data

Contoso, Ltd. and its people (Kim Akers, Debra Garcia, Garth Fort, and Katie Jordan) are made up. See [NOTICE.md](../NOTICE.md).

Found a step that no longer matches GitHub.com or Visual Studio Code? Open an issue with the *Content question or demo issue* template.
