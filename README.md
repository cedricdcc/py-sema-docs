# py-sema Documentation

Documentation site for [py-sema](https://github.com/vliz-be-opsci/py-sema) built with [Mintlify](https://mintlify.com).

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview documentation changes locally:

```bash
npm i -g mint
```

Run the development server at the root of this folder:

```bash
mint dev
```

The preview will be available at `http://localhost:3000`.

## Validation

Validate documentation syntax, MDX content, and configuration:

```bash
mint validate
```

## Structure

- `docs.json`: Mintlify configuration (theme, navigation, branding)
- `index.mdx`: Project introduction and capability overview
- `quickstart.mdx`: Installation and getting started walkthrough
- `cli/`: Reference pages for core command-line tools (`sema-bench`, `sema-harvest`, `sema-subyt`, `sema-query`, `sema-get`, `sema-syncfs`)
- `utilities/`: Specialized tools (`ro-crate`, `reason`, `aggregation`, `conneg`)
- `python-api/`: Python programmatic usage, commons, and architecture/migration guide
