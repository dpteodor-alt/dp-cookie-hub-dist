# dp-cookie-hub-dist

The public, signed knowledge bundle of the cookie hub (ADR-064). Published by `bundle.yml` of the private `dp-cookie-hub`; nothing here is edited by hand.

- `bundle.json` — vendors, approved categorisations and the Open Cookie Database (Apache-2.0, `LICENSE-open-cookie-database.txt`). No client or site names.
- `bundle.json.sig` — detached Ed25519 signature (base64). Sites (dp-core `Monitor\Hub`) accept a bundle only with a valid signature and a higher `version` than the one they have.
