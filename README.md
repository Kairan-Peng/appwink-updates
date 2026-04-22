## AppWink Updates

This repository hosts the public Sparkle update feed and release assets for AppWink.

Published content:

- `appcast.xml`
- `downloads/`
- `release-notes/`
- `license/appwink-license-endpoints.json`

The main AppWink source repository can remain private. Only the signed release assets, Sparkle metadata, and public license endpoint-discovery hint are published here.

`license/appwink-license-endpoints.json` is intentionally only a server-location hint for the direct-license client. The app still requires the selected license server to return an Ed25519-signed manifest before trusting the endpoint.
