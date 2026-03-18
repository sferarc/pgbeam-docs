---
title: PgBeam Documentation
unlisted: true
---

# PgBeam Documentation

Source files for [docs.pgbeam.com](https://docs.pgbeam.com) — the documentation
for PgBeam, a globally distributed PostgreSQL proxy platform with connection
pooling and query caching.

## Structure

```
.
├── index.mdx              # Getting started
├── cache.mdx              # Query caching
├── pooling.mdx            # Connection pooling
├── routing.mdx            # Read/write routing
├── replicas.mdx           # Read replicas
├── api/                   # API reference (auto-generated)
├── cli/                   # CLI reference (auto-generated)
├── go-sdk/                # Go SDK reference (auto-generated)
├── ts-sdk/                # TypeScript SDK reference (auto-generated)
├── terraform.mdx          # Terraform provider guide
├── crossplane.mdx         # Crossplane provider guide
├── pulumi.mdx             # Pulumi provider guide
└── meta.json              # Navigation and metadata
```

## Contributing

Documentation is written in MDX (Markdown + JSX). Pages use
[Fumadocs](https://fumadocs.vercel.app/) conventions.

To preview locally, run from the monorepo root:

```bash
pnpm dev
```

## License

Apache 2.0 — see [LICENSE](LICENSE).
