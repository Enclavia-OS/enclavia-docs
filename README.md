# Enclavia Docs

Public customer documentation for Enclavia, served at `docs.enclavia.xyz`.

Static site (plain HTML + Tailwind via CDN), deployable with GitHub Pages.

## Publishing

1. Create a public GitHub repo from this directory (e.g. `Enclavia-OS/enclavia-docs`).
2. In repo **Settings → Pages**, set **Source** to `main` branch, `/ (root)`.
3. Add a DNS `CNAME` record for `docs.enclavia.xyz` → `<org>.github.io`.
4. Push. The `CNAME` file already points at `docs.enclavia.xyz`.

## Pages

- `index.html` — getting started: the minimum changes to go live.
- `deployment.html` — deploying the stack in the customer's VPC + operations.
- `agent.html` — agent integration (native HTTP, `@enclavia-os/cli`, and the optional Python zero-code hook).
