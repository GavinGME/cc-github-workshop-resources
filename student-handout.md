# GitHub workshop handout

Part 1  Repository and documentation

Beginner: make a harmless practice repository. Experienced: improve a repository you own and are allowed to edit. Draft locally or pair if account access is blocked.

## Account and repository

1. Sign in or create/verify your account. Add a brief, honest bio.

2. Create cc-github-lab under your personal account. Add a description and README. Choose public or private deliberately.

3. Edit README.md with a purpose sentence. Preview, review the change, then commit: Add workshop purpose.

4. Create learning-log.md with one takeaway. Commit: Add learning log.

5. Open history and one diff. Explain what changed and why the message fits.

## Improve the README

- Purpose: what does it do and why?

- Use: steps, requirements, or a file guide.

- Evidence: safe example input/output or a result.

- Contribution: your actual role.

- Limits and one next step.

## Partner test

Give your partner 30 seconds without a spoken tour. Ask them to state the purpose and find the next step. Clarify one sentence and commit.

Copyable templates: https://github.com/GavinGME/cc-github-workshop-resources
Finished example: https://github.com/GavinGME/cc-github-example

# GitHub workshop handout

Part 2  Safety and profile

## Before publishing

- Read contents and diffs. Check screenshots, sample data, history, and permission to share.

- Keep live credentials and private keys out. Use synthetic data and blank configuration examples.

- Check class/CTF publication rules. Keep uncertain material private while reviewing.

## Safe configuration starter

```text
.env
.env.*
!.env.example
*.pem
*.key
id_ed25519
id_rsa
```

Create .gitignore with relevant rules. Create .env.example with API_TOKEN= and API_BASE_URL= and blank values. Review and commit only safe files.

Ignore rules guide untracked local files. They do not remove tracked files, erase history, encrypt files, or protect browser uploads automatically.

## Profile README

1. Create a public repo named exactly your username, with a nonempty root README.md. Existing one? Edit it.

2. Introduce your current focus. Link real work and describe what you personally did.

3. Profile > Customize your pins. Choose relevant, reviewed public work and test links.

Public details are optional. You can keep a private draft. If a real secret leaked, invalidate it or contact its owner immediately, then coordinate cleanup.

# GitHub workshop handout

Part 3  Review and next milestone

## One-minute reviewer

- Find purpose, author's role, evidence, and the first step.

- Give one specific strength and one useful improvement. Switch roles.

- Keep account control with the owner. No need to execute unfamiliar code.

Feedback: The clearest evidence is ___. I could not find ___. One change that would help is ___.

## Final checklist

- Account/repository purpose checked.

- Two useful changes and meaningful messages.

- README explains use or the files.

- Secrets and permission reviewed.

- Profile README ready or drafted. Pins checked if used.

- One achievable next step selected.

## My progress

Repository link: ____________________________________________

One improvement I made: ____________________________________

My next milestone: _________________________________________

When I will do it: __________________________________________

## Optional branch and pull request

In your owned practice repo: branch docs-improvement from main, edit/commit on that branch, open PR with base main and compare docs-improvement, review the diff, then merge if allowed.
