# hl-whale-dash

Static dashboard for an `hl-whale-watcher` instance (see that private repo):
live book + equity from the Hyperliquid public API, the $1K paper copy and
alert stream from the watcher's ntfy topics. Generic by design — the topic and
watched address are supplied via the URL fragment (`#t=<topic>&a=<address>`)
or entered once and kept in localStorage; the page source contains neither.

Hosted on GitHub Pages from this repo. No backend, no keys, read-only.
