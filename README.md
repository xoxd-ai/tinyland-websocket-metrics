# tinyland-websocket-metrics (RETIRED)

**Retired 2026-10-14.** This package is no longer maintained and this repository is archived.

- No live repository consumes it, and it has no replacement module. For metrics, use the Bazel module
  `tummycrypt_tinyland_otel` (`@tummycrypt/tinyland-otel`, including its `./prometheus` export).
- The Bazel registry module `tummycrypt_tinyland_websocket_metrics` (xoxd-ai/bazel-registry) is marked
  `deprecated`. Version 0.2.2 stays resolvable; nothing is yanked.
- In-house packages are distributed through the Bazel registry only. The npm publish workflow has been
  removed and the package is marked `private`. Versions 0.2.0-0.2.2 already on npmjs stay as they are.

Original description: WebSocket connection metrics collector with Prometheus export.
