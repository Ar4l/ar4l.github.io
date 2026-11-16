# aral.cc

My portfolio at [aral.cc](https://aral.cc), plus the apps it hosts.

- **Portfolio:** [`index.md`](index.md) at the repo root, rendered with [`_layouts/default.html`](_layouts/default.html).
- **Talks:** slides in [`talks/`](talks/), served at `aral.cc/talks/<file>.pdf`.
- **[Battleship](https://aral.cc/battleship/):** peer-to-peer Battleship in [`apps/battleship/`](apps/battleship/). Its README covers development.

[`pages.yml`](.github/workflows/pages.yml) deploys on every push to `main`. It tests and builds each app, renders the portfolio with Jekyll, and publishes the portfolio at `/` and each app at `/<name>/`.
