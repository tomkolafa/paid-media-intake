# Paid Media Client Intake

A single-page static intake form used at the start of paid-media engagements. Clients fill it out and the page commits the submission directly to a private skills repo (`tomkolafa/skills`) via the GitHub API using a personal access token (PAT) supplied at runtime — no backend, no third-party form service.

**Live URL:** https://tomkolafa.github.io/paid-media-intake/

## Notes

- The page commits intake submissions to the **private** [`tomkolafa/skills`](https://github.com/tomkolafa/skills) repo via PAT auth (provided per-session by the operator, not embedded in the page).
- The page sets `<meta name="robots" content="noindex, nofollow, noarchive, nosnippet">` to keep it out of search results.
- Hosted via GitHub Pages from `main` branch root.
