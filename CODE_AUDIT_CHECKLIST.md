# Free Code Audit Checklist

- [ ] Record the repository root, languages, package manager, test command, and CI entrypoint.
- [ ] Search for hardcoded keys, passwords, tokens, and sensitive values in source and configuration.
- [ ] Parse Python files and flag syntax errors and bare `except:` blocks.
- [ ] List public functions and confirm each has a focused unit or integration test.
- [ ] Trace routes, handlers, services, persistence, jobs, environment variables, and feature flags.
- [ ] Review authorization, input validation, unsafe shell calls, path traversal, deserialization, and sensitive logs.
- [ ] Run the full test suite and record failures with exact commands.
- [ ] Separate static-analysis signals from runtime proof.

For the full 14-point protocol and Markdown/JSON scorecards, use the [Autonomous Code Auditor Skill Pro](https://gumroad.com/l/autonomous-code-auditor-skill-pro).
