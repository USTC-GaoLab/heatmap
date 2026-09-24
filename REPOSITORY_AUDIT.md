# Repository structure audit

Repository:

`heatmap`

Current structure:

- The repository contained documentation but no committed R implementation or examples.
- No notebooks, configuration files, raw data, results, or files larger than 50 MB were found.

Problems:

- Package code, examples and documentation had no separate locations.
- Environment and license files were missing.

Recommended structure:

```text
R/
examples/
docs/
```

Migration actions:

- Created tracked `R/` and `examples/` locations.
- Moved tool review and structure documents into `docs/` with `git mv`.
- Added environment, license and repository-audit documentation.
- No scientific code or data was deleted or uploaded.
