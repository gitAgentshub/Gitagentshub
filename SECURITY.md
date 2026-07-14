# Security Policy

## Supported Versions

This is a single-page front-end project without versioned releases. Security fixes are applied to the `main` branch.

## Reporting a Vulnerability

If you discover a security vulnerability, please **do not** open a public issue. Instead:

1. Open a private security advisory via the repository's "Security" tab, or
2. Contact the maintainer directly

Please include:

- A description of the vulnerability
- Steps to reproduce
- Potential impact

We'll aim to acknowledge reports within a few days.

## Known Limitations

- The authentication demo in `index.html` stores user data in-memory on the client only. It is **not** secure and is not intended for production use as-is.
