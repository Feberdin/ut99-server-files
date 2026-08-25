<!--
Purpose: Document the current placeholder state of ut99-server-files.
Input/Output: Repository metadata and security automation enter; no server runtime artifact is currently published.
Invariants: Do not commit proprietary game files, credentials, saves, logs, or generated archives.
Debugging: Inspect Git history and the secret-scan workflow; there is currently no application build or runtime.
-->

# ut99-server-files

This repository is currently a protected placeholder for future Unreal
Tournament 99 server configuration. It contains no deployable server files.

## Quickstart

There is nothing to install or start yet. Add only redistributable configuration
and documentation after confirming the relevant game-file license.

## Configuration, troubleshooting, and debugging

No runtime configuration, logs, ports, or service commands currently exist.
GitHub Actions runs the central secret scan on repository changes.

## Security

Never commit server passwords, admin tokens, private player data, logs, saves,
or proprietary game assets. Report vulnerabilities through [SECURITY.md](SECURITY.md).

## License

No license grant is currently included. All rights remain reserved, and
third-party Unreal Tournament assets must not be redistributed without permission.
