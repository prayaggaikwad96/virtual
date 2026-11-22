# Security Policy

## Scope

This repository is a fork of TanStack Virtual. Security reports concerning code maintained only in the upstream project should be reported to the upstream maintainers as well as the fork maintainer where the fork-specific change is relevant.

## Reporting a vulnerability

Please do not publish credentials, private data, exploit payloads, or unpatched vulnerability details in a public issue or pull request.

For a private report, use GitHub's **Report a vulnerability** option in this repository's **Security** tab when private vulnerability reporting is available. If the option is unavailable, contact the repository owner through the GitHub profile and request a private disclosure route. For issues that also affect upstream TanStack Virtual, follow the upstream project's security policy.

A useful report includes the affected commit or package version, the impacted workflow or component, the security impact, safe reproduction steps, and a proposed mitigation where known. Do not include real user data or active credentials.

## Supported versions

Security fixes are prioritized for the current default branch and the latest published fork release, where applicable. Older commits and branches are not guaranteed to receive fixes.

## Secrets and credentials

Never commit tokens, API keys, signing keys, private registry credentials, or other secrets. If a credential is exposed, revoke or rotate it immediately; removing the file or commit does not invalidate the credential.

## Response expectations

Reports are reviewed as time and severity permit. No fixed response-time or remediation SLA is promised. Please allow reasonable time for assessment and coordinated disclosure.
