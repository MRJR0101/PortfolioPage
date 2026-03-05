# Contributing

This is a personal portfolio site. It's a single HTML file (`index.html`) with
inline CSS -- no build step, no dependencies, no framework.

## Making Changes

1. Edit `index.html` directly.
2. Open it in a browser locally to verify it looks right before committing.
3. Keep commits focused -- one change per commit with a clear message.
4. Do not introduce external scripts, tracking pixels, or third-party analytics.

## What Belongs Here

- Updates to portfolio content (projects, bio, stats)
- CSS/layout improvements to `index.html`
- README or documentation updates

## What Does Not Belong Here

- Internal file paths or references to local systems
- API keys, credentials, or environment-specific config
- Build artifacts or cache directories
- Frameworks, npm, or bundlers -- this site intentionally has no build step

## Tests

The smoke test (`tests/test_smoke.py`) just checks the README exists.
Run with: `pytest tests/`
