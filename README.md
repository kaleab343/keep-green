# keep-green

A tiny repo whose GitHub Action commits once a day so the contribution
grid stays green. See `.github/workflows/daily-commit.yml`.

Commits count on the profile grid only when the commit **author email**
is verified on the GitHub account — that's set in the workflow env
(`COMMIT_EMAIL`). Bot commits do NOT count.
