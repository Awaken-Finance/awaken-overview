# Awaken Overview

A concise introduction to Awaken's exchange design on aelf.

[Read the guides](https://awakenfinance.gitbook.io/en/) · [Explore the contracts](https://github.com/Awaken-Finance/awaken-swap-contract) · [View blockchain records](https://aelfscan.io/)

## Exchange concepts

- **Swaps:** how liquidity pools exchange one token for another.
- **Liquidity:** how paired assets and LP tokens represent a position in a pool.
- **Limit orders:** how target exchange rates and expiry conditions define an order.

The landing page connects these ideas to the documentation and contract code. Individual topic pages provide more context.

## Open the site

```sh
python3 -m http.server 4177 --bind 127.0.0.1
```

Run the command from this directory, then visit [localhost:4177](http://127.0.0.1:4177/). The files can also be published directly to a static host. On GitHub Pages, choose the publishing branch and `/(root)`; navigation and assets use relative paths.

## Files and artwork

`index.html` contains the overview, `landing.css` defines the hero layout, and `routes/topics.css` styles the topic pages. `static-manifest.json` lists the pages, resources, and checksums.

Roboto and the landing artwork originate from the [Awaken website](https://github.com/Awaken-Finance/awaken-website); the project mark comes from the [Awaken frontend](https://github.com/Awaken-Finance/awaken-frontend).
