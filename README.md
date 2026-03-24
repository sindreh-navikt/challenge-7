# build-orchestrator

Internal multi-stage build orchestration service. Coordinates preparation and build jobs for all pull requests.

## Development

```bash
npm install
npm run build
```

## CI

Pull requests trigger a two-stage pipeline: a preparation stage that packages build assets, followed by the main build. Check the Actions tab for full pipeline status.

## Bugs & Support

Found a bug or have a question? [Open an issue](../../issues/new) and we'll get back to you.
