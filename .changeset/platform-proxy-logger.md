---
"wrangler": minor
---

Allow supplying a Miniflare logger to `getPlatformProxy()`

Pass a Miniflare `Log` instance via the optional `log` property to capture messages from local bindings, such as file paths from simulated emails. A custom logger can filter or redirect those messages, and omitting the option keeps Miniflare logging disabled.
