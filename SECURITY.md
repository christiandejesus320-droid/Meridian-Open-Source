# Meridian Security Policy

## Scope

This repository is the public documentation and community surface for Meridian. It does not contain the private engine, production infrastructure, customer data, or credentials.

## Do Not Publicly Disclose

Never publish API keys, tokens, passwords, `.env` files, database exports, customer data, internal URLs, private repository links, production logs, access-control details, or private engine source code. Do not attempt to reconstruct or infer private implementation details from public behavior.

## Reporting a Security Concern

Do not open a public Issue or Discussion for a suspected vulnerability or exposed secret. Contact the project maintainers through the private security contact configured in the repository's GitHub Security settings. Include a concise description, affected public surface, reproduction steps that do not require sharing secrets, and any safe mitigation you can recommend.

If a credential has been exposed, revoke or rotate it immediately through the owning provider and then report the incident privately. Do not paste the credential into the report.

## Public-Surface Review

Before opening a pull request, inspect the diff for secret-like values, private hostnames, email addresses that should not be public, customer identifiers, copied source code, and generated files. When in doubt, stop and ask maintainers privately.

## Response

Maintainers will acknowledge reports, assess impact, coordinate remediation, and publish a public explanation only when doing so is safe. The Zero-Code Exposure rule remains in force during investigation.
