# triage-sandbox
Throwaway repo for testing RadiantOps Triage. No real code.

## Running the check locally

From the repository root, run:

```sh
test -f README.md
```

This matches the check in `.github/workflows/ci.yml`, which runs on
`ubuntu-latest` after `actions/checkout@v4`. The command exits with status 0
if `README.md` exists as a regular file, or status 1 otherwise.
