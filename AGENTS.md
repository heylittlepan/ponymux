# Repository guidelines

This repository contains PonyMux product information and community resources.

- Write documentation and commit messages in English.
- Use Conventional Commits, such as `docs: clarify agent setup`.
- Publish commits as `heylittlepan` using `316232801+heylittlepan@users.noreply.github.com` for both author and committer.
- Use repository-local Git settings. Keep global Git and GitHub authentication settings unchanged.
- In the publication checkout, use `.git/libexec/gh-ponymux` for authenticated GitHub CLI operations. Do not use the globally authenticated `gh` for repository writes.
- If that local helper is unavailable, configure a repository-scoped credential before publishing; do not fall back to another account.
- The publication remote is `https://github.com/heylittlepan/ponymux.git`.
- Keep application source code, credentials, internal links, and private information out of this repository.
- Read `docs/MAINTENANCE.md` before changing product information or release summaries.
