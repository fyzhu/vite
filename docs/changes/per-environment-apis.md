# Dev Server APIs

::: tip Feedback
Give us feedback at [Environment API feedback discussion](https://github.com/vitejs/vite/discussions/16358)
:::

Multiple APIs from ViteDevServer related to module graph has replaced with more isolated Environment APIs.

- `server.moduleGraph` -> [`environment.moduleGraph`](/guide/api-vite-environment#separate-module-graphs)
- `server.transformRequest` -> `environment.transformRequest`

Affect scope: `Vite Plugin Authors`

::: warning Future Deprecation
The Environment instance was first introduced at `v6.0`. The deprecation of `server.moduleGraph` and other methods that are now in environments is planned for `v7.0`. We don't recommend moving away from server methods yet. To identify your usage, set `future.deprecationWarnings` in your vite config.
:::

## Motivation

// TODO:

## Migration Guide

// TODO: