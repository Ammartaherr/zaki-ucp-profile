# Personal shopping agent profile (UCP)

Public agent profile for a private, single-user home assistant ("Zaki") that shops on UCP-enabled Shopify stores
for its owner. Served via GitHub Pages so stores can fetch it during UCP capability negotiation.

- No payment handlers are declared: this agent never handles payment credentials.
- It searches catalogs and builds carts/checkouts, then hands the checkout link to its owner, who pays personally.
- Personal use only. No resale, aggregation or commercial use.
- `signing_keys` holds a public key only. The private key is never published.
