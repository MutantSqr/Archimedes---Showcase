# Security and Disclosure

The production Archimedes source, runtime configuration, integrity manifests, memory, audit data, credentials, device identifiers, and handoff secrets are not stored in this public repository.

This repository must never receive:

- executable Archimedes core source;
- local configuration or `.env` files;
- API keys, tokens, passwords, or credentials;
- memory or audit-log exports;
- private device names or identifiers;
- handoff state files or one-time tokens;
- raw reports containing private filesystem paths.

Security concerns may be reported privately to the repository owner through their GitHub profile.
