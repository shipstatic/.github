Most people arrive here the same way: they asked an AI coding assistant to put an HTML report, prototype, or small website online, and it found the shortest path.

```bash
npx @shipstatic/ship ./dist
```

No installation, no account, no API key, no configuration. The coding agent can publish immediately and, seconds later, you have a real, public URL to share.

Need to share privately? Just add `--password`. The site will ask for it before anyone can access it, perfect for client drafts, reports, and works in progress.

If your coding agent prefers tools over terminal commands, it can use `@shipstatic/mcp`. ShipStatic publishes your static files exactly as they are, so simply point it at `./dist`, `./out`, `./public`, or `.`.
