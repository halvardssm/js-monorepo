# js-monorepo

Tools and functions that have personal use

## openapi2fetch

Generates a fetch client using `openapi-typescript` and `openapi-fetch`.

```ts
deno run -A jsr:@halvardm/openapi2fetch --src ../bitwarden-sdk/spec.json --out ../bitwarden-sdk/mod.ts
```

## bitwarden-sdk

A bitwarden sdk using typescript-fetch generated from openapi specs using
typescript-openapi
