# Documentation project instructions

## About this project

- This is the documentation site for `py-sema`, built on [Mintlify](https://mintlify.com)
- The target repository is located at `../py-sema` (Open Science Team VLIZ vzw)
- Pages are MDX files with YAML frontmatter
- Site configuration lives in `docs.json`
- CLI tools documented: `sema-bench`, `sema-harvest`, `sema-subyt`, `sema-query`, `sema-get`, `sema-syncfs`, `sema-roc`, `sema-ro-get`, `sema-reason`, `sema-aggregate`, `sema-conneg`

## Terminology

- Use `py-sema` (or `pysema` when referring strictly to the package/distribution name)
- Use standard semantic web terms: RDF, Turtle, SPARQL, Triplestore, Named Graph, RO-Crate, SHACL
- Use `sema-bench` for pipeline orchestration (replaces legacy `sembench`)
- Use `sema-harvest` for path traversal & harvesting (replaces legacy `travharv`)
- Use `sema-subyt` for templating triples (replaces legacy `pysubyt`)
- Use `sema-query` for tabular extraction (replaces legacy `kg2tbl`)
- Use `sema-get` for web discovery (replaces legacy `webdiscovery`)
- Use `sema-syncfs` for filesystem triplestore synchronization (replaces legacy `syncfstriples`)

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Code formatting for CLI commands, file names, options, and code symbols (e.g. `sema-bench`, `docs.json`, `--config`, `Harvest`)
- Use Mintlify MDX components (`<CardGroup>`, `<Card>`, `<Steps>`, `<Step>`, `<Tip>`, `<Note>`, `<CodeGroup>`) appropriately

## Content boundaries

- Document user-facing CLI commands, options, YAML configuration schemas, and public Python service APIs
- Do not document internal temporary test fixtures or undocumented private helpers
