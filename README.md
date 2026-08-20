# SpoofSense API documentation

Public developer docs for the [SpoofSense](https://spoofsense.ai) face liveness and deepfake detection API. Built with [Mintlify](https://mintlify.com); deployed automatically on push to `main`.

## Structure

- `docs.json` — site config and navigation
- `*.mdx` — documentation pages
- `api-reference/openapi.json` — OpenAPI 3.1 spec; the API-reference tab is generated from it

## Local preview

```bash
npm i -g mint
mint dev
```

## Keeping docs in sync

The API source of truth lives in the (private) `spoofsense-web-app` repo under `api/`. When endpoints, error codes, or credit costs change there, update the affected pages and `api-reference/openapi.json` here.
