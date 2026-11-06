# Deployment

A library and CLI. Not a hosted app.

npm package `subtext-scan`. `publishConfig.access` is public and provenance
is on. The release workflow is `.github/workflows/release.yml`. The package
files are `bin/`, `src/`, `README.md`, `LICENSE`, and `NOTICE`.

Until the first npm release, the README documents the GitHub release tarball
`subtext-scan-0.1.0.tgz`.

CI builds `infra/docker/Dockerfile` and runs the suite. There is no image
registry and no production environment. Rollback of `main` is `git revert`.
