# tutti-os CodeRabbit Configuration

Central CodeRabbit configuration for the `tutti-os` GitHub organization.

CodeRabbit automatically looks for `.coderabbit.yaml` in a repository named
`coderabbit` under the organization. This repository is intended to provide
shared defaults for all `tutti-os` repositories.

## Review Policy

- Normal repositories: inline comments should be limited to P0/P1 findings.
- Tutti workspace apps: use `tutti-os/tutti-agent-skills` as the contract source
  when PRs touch `tutti.app.json`, `tutti.cli.json`, `bootstrap.sh`, packaging,
  runtime environment handling, or release workflows.
- Lower-priority observations should go in summaries or be omitted.
- English is the default for this public open-source organization. Chinese is
  still allowed when the PR discussion is primarily Chinese.

## Notes

Repository-local `.coderabbit.yaml` files can override this central config. Add
`inheritance: true` in repository configs when they should merge these defaults
instead of replacing them.
