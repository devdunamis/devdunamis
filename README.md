# Hi, I'm Dunamis Olatunde 👋

I'm a solo WordPress engineer based in Ibadan, Nigeria, building production SaaS platforms for African and global clients.

In the past year I've shipped three live platforms — solo, end-to-end, on shared hosting:

🏛 **[ChurchVault](https://dunamiscodevisuals.com/work/churchvault.html)** — multi-tenant church finance SaaS · multi-currency (₦/$/£) · recurring Paystack billing · live with paying customers

🌍 **[Vault Core](https://dunamiscodevisuals.com/work/vaultcore.html)** — four-module fintech platform · 2-person expense approval at the database layer · 8-country tax engine · built for the African market

💕 **[Kisses & Huggs Club](https://dunamiscodevisuals.com/work/khc.html)** — faith-based community platform · 3-stream affiliate system · currency-aware Paystack routing · launched May 2026

Together: **53+ custom plugins, ~22,000 lines of solo-authored PHP**, multi-tenant architectures, idempotent webhooks, Paystack-native subscriptions in NGN and USD.

---

### How I build

🔧 **Native WordPress APIs end-to-end** · `$wpdb` prepared statements, nonces, capability checks, WP-Cron — no boilerplate frameworks, no off-the-shelf membership plugins

⚡ **Database-first discipline** · idempotency lives in composite UNIQUE keys, not in application locks

🎯 **No build pipelines** · no Composer, no npm, no Webpack — every change is a file edit; the platform will run in three years without dependency rot

🛡️ **Security by default** · HMAC-verified webhooks, capability gates everywhere, defensive permission checks at every read and write

---

### Repositories here

- **[wp-plugin-boilerplate](https://github.com/devdunamis/wp-plugin-boilerplate)** — opinionated starter for serious plugins. Schema migrations, prepared statements, idempotent webhooks, capability checks. Distilled from production work.

- **[multi-tenant-query-helper](https://github.com/devdunamis/multi-tenant-query-helper)** — the discipline-as-code pattern I use for tenant isolation in WordPress: resolve the allowed tenant IDs once, then filter every query through a prepared `IN` clause.

---

### Available for senior engagements

Custom WordPress plugins. SaaS architectures with Paystack billing. Multi-tenant platforms. Custom REST APIs with HMAC verification. Performance and database optimization. WordPress security incidents (malware removal, hacked-site recovery, hardening) and migration/rescue work.

📂 **Portfolio & case studies:** [dunamiscodevisuals.com](https://dunamiscodevisuals.com)
📧 **Email:** [dev@dunamiscodevisuals.com](mailto:dev@dunamiscodevisuals.com)
💼 **LinkedIn:** [linkedin.com/in/pastordunamis](https://www.linkedin.com/in/pastordunamis/)
