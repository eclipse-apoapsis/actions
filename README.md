# Eclipse Apoapsis GitHub Actions

## `setup-osc`

This action provides an easy way to use the [ORT Server Client (OSC) CLI](https://eclipse-apoapsis.github.io/ort-server/docs/user-guide/cli/getting-started) in a GitHub workflow.

### Download

- `osc-version`: The version of OSC to set up, defaults to `latest`.

#### Configuration

The action can be configured to use authentication with the ORT Server instance using the following options:

- `url`: The base URL of the ORT Server instance.
- `username`: The username to use for authentication.
- `password`: The password to use for authentication.
- `token-url`: The URL to request a token for the ORT Server instance (optional).
               Only required if using a custom Keycloak instance.
- `client-id`: The client ID to use for authentication (optional).
               Only required if using a custom Keycloak instance.
