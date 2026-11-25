# SvelteKit on Deno

Example [SvelteKit](https://svelte.dev/docs/kit) app running on [Deno](https://deno.com/). SvelteKit is the official framework for building full-stack apps with Svelte. Deno is a secure JavaScript and TypeScript runtime with built-in tooling and Node.js compatibility.

## Deploy settings

| Field | Value |
| --- | --- |
| Build | Static site — Railpack build |
| Single-page application (SPA) | off |
| Project directory | `/` |
| Output directory | `/build` |
| Install command | leave empty |
| Build command | `deno task build` |
| Health check path | `/` |

## <a name="dev"></a>Run locally

```bash
# install dependencies
deno install --allow-scripts

# build for production
deno task build
```
