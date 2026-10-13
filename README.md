# Goliath documentation

User documentation for the Goliath loader. Built with Mintlify and published from this repository's `main` branch.

## Preview and check

Install Node.js 20.17 or newer, then install the Mintlify CLI:

```sh
npm install -g mint
mint dev --no-open
```

Before publishing:

```sh
mint validate
mint broken-links
```

## Content

- `docs.json`: navigation, colours and branding.
- Root MDX pages: accounts, licence keys, trials, products, updates and resets.
- `troubleshooting/`: the loader's approved error messages.
- `images/your-products.png`: a preview account, not live customer data.
- `logo/` and `favicon.svg`: Goliath branding.

Reset requests go to a seller who handles them through the bot. The download button uses the loader URL provided by the owner. External support links are intentionally omitted. Screenshot reports are not covered in this site.

Changes pushed to the connected branch are published by Mintlify. The site's public URL is available in the Mintlify dashboard and deployment checks.
