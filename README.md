# DAOhaus Developer Docs

Source for the DAOhaus developer documentation site at [docs.daohaus.club](https://docs.daohaus.club/).

These docs cover the technical infrastructure of the DAOhaus protocol: smart contracts, subgraphs, and contribution workflows for maintainers.

## Stack

Built with [Next.js](https://nextjs.org/) and [Nextra](https://nextra.site/). Content lives in `pages/` as `.mdx` files.

## Local Development

```bash
pnpm install
pnpm dev
```

The site will be available at `http://localhost:3000`.

## Contributing

Content is organized under `pages/`:

- `contracts/` — Moloch v3 (Baal) contract reference, deployments, shamans, summoners
- `subgraphs.mdx` + `subgraphs/` — Subgraph schema, endpoints, and example queries
- `networks.mdx` — Supported networks
- `contributing/` — SOPs for app, subgraph, and contract maintenance

To add or edit a page, update the relevant `.mdx` file and its `_meta.json` to control where it appears in the sidebar.
