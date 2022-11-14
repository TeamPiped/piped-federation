# piped-federation

All information about Piped's federation protocol on Matrix.

## How to join?

Register on a homeserver with no rate-limiting, or create your own homeserver.

If you would like an account on the `federation.piped.video` homeserver, message [@kavin1337:matrix.org](https://matrix.to/#/@kavin1337:matrix.org) on Matrix.

Set the homeserver URL in `config/config.properties` with the `MATRIX_SERVER` property.
Example: `MATRIX_SERVER: https://homeserver-domain.org`

Set the Matrix Access Token with the `MATRIX_TOKEN` property.
Example: `MATRIX_TOKEN: ABCDEFGHIJKLMNOPQRSTUVWXYZ`
- To get the Access Token using Element, go to Settings > Help & About > Advanced

Restart your Piped backend.

Send a PR to add your account to the [authorized-users.json](/authorized-users.json) file.

## Recommended homeservers to Host

Conduit: https://conduit.rs/
