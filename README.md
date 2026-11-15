# Haytham Labs

The Haytham Labs organization website is a dependency-free static site.

## Netlify

Import `haytham-labs/haytham-labs.github.io` in Netlify. The repository-root
`netlify.toml` publishes this directory directly, with no build command or
environment variables required. Deploy the `main` branch to enable automatic
deploys on future pushes.

## Local preview

Serve this directory with any static file server, for example:

```sh
python3 -m http.server 8000
```
