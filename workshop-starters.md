# CC GitHub workshop starters

Use these during the University of Montana Cybersecurity Collective workshop. Replace the sample wording with accurate details. Preview Markdown before committing.

## Project README

```markdown
# Project name
One sentence explaining what this project does and why I built it.

## How to use
Prerequisites and steps, or a guide to exploring the files.

## Example result
Synthetic sample input and expected output, or a sanitized screenshot.

## My contribution
What I personally built, investigated, or documented.

## Limitations
Known gaps, assumptions, and authorized-use scope.

## Next step
One specific improvement.
```

## Profile README

Create a public repository with the exact same name as your GitHub username and add a root `README.md`, or edit the one you already have. Draft privately if you prefer.

```markdown
# Hi, I'm YOUR NAME
I'm a University of Montana student interested in YOUR INTEREST.

## Current work
I'm learning YOUR TOPIC through YOUR ACTUAL PROJECT.

## Featured project
[PROJECT NAME](YOUR REAL PROJECT URL): what I built and what it demonstrates.

## Next step
One concrete thing I plan to learn or improve.
```

## .gitignore starter

```gitignore
.env
.env.*
!.env.example
*.pem
*.key
id_ed25519
id_rsa
```

Adapt these patterns to your project. This is not an exhaustive list. `.gitignore` affects untracked files in local Git workflows. It does not prevent browser uploads, remove tracked files, or erase history. Review every diff.

## .env.example

```dotenv
API_TOKEN=
API_BASE_URL=
```

Use blank values or harmless placeholders. Never use working credentials. Do not create a real secret for this activity.

## Peer review

- I found the project purpose in ___ .
- I found the author's contribution in ___ .
- I could / could not follow the usage or exploration steps because ___ .
- One confusing or unsafe detail is ___ .
- One useful improvement is ___ .

## Before publishing

- Review contents and diffs for credentials, private keys, personal data and restricted material.
- Sanitize screenshots and logs, including identifiers and metadata.
- Check coursework, CTF and third-party sharing permissions.
- Use synthetic sample data.
- If a credential leaks, revoke or rotate it first, notify its owner, and coordinate cleanup. Deleting the file is not enough.

Official guidance: [Ignoring files](https://docs.github.com/en/get-started/git-basics/ignoring-files), [Removing sensitive data](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/removing-sensitive-data-from-a-repository), [Profile README](https://docs.github.com/en/account-and-profile/how-tos/profile-customization/managing-your-profile-readme).


## Finished workshop example
https://github.com/GavinGME/cc-github-example

This is a supplied teaching example. Explain your own changes when adapting it.
