# Profile maintenance

[README.md](../README.md) is the GitHub profile entry point. It links inspectable
DevOps, MLOps and AI engineering projects and records professional experience.

## Review changes

- Confirm employment dates, role descriptions and numerical claims against source
  records before editing them.
- Keep project descriptions consistent with code, tests and documented limitations.
- Link to reproducible evidence; distinguish implementation tests from measured
  model quality and production deployment results.
- Keep private client code and credentials out of this public repository.

```bash
make verify
```

This checks documentation whitespace. There is no executable application here.
The dated quality review in `docs/` is a snapshot; follow its pull-request links
for current publication and CI status.
