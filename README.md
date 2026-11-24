# React on Deno

Example [React](https://react.dev/) app running on [Deno](https://deno.com/). React is a JavaScript library for building user interfaces from components. Deno is a secure JavaScript and TypeScript runtime with built-in tooling and Node.js compatibility.

## Deploy settings

| Field | Value |
| --- | --- |
| Build | Static site — Railpack build |
| Single-page application (SPA) | off |
| Project directory | `/` |
| Output directory | `/dist` |
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
