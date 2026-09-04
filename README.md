---
title: PgBeam Documentation
unlisted: true
---

# PgBeam Documentation

Source files for [pgbeam.com/docs](https://pgbeam.com/docs), the documentation for PgBeam, a Postgres proxy for safe AI agent access with policy enforcement in the wire protocol. It is also globally distributed and provides connection pooling and query caching.

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

Issues and pull requests are welcome here. An issue is the right place to start for a page that is wrong, missing, or out of date; link the page and say what it should have told you.

Pages are MDX (Markdown plus JSX) and follow [Fumadocs](https://fumadocs.vercel.app/) conventions. The `api/`, `cli/`, `ts-sdk/`, and `go-sdk/` sections are reference material built from the API contract and the CLI command definitions, so corrections to those are best filed as an issue naming the operation or command.

Do not open a public issue for a suspected security vulnerability. Email security@pgbeam.com, or report it privately from this repository's Security tab.

## License

Apache 2.0 — see [LICENSE](LICENSE).
