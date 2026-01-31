# Security Policy

This repository contains infrastructure-as-code and GitOps examples (Kubernetes/Flux/Terraform/SOPS).

## Reporting a vulnerability

If you believe you’ve found a security issue, please **do not open a public issue**.

Instead, contact the maintainer privately:

- Open a GitHub security advisory (preferred) if enabled for the repo, or
- Email: **TBD**

Include:

- A clear description of the issue and impact
- Reproduction steps / proof-of-concept (if available)
- Any logs or relevant configuration snippets (please redact secrets)

## Secrets

- **Never commit plaintext secrets** to this repository.
- If a secret is required, store it encrypted with SOPS (Age) and ensure it matches the repository’s `.sops.yaml` rules.
- If you suspect a secret was exposed, treat it as compromised and **rotate it immediately**.

## Supported versions

This is a personal homelab repo/template. Security fixes may land on `main` without backporting.

