# Security Policy

This repository is a BlockGrain-owned maintenance fork of NHN TOAST UI Calendar. It exists primarily to preserve source and package availability for BlockGrain/Agrichain products after the upstream project was archived.

## Supported Artifacts

| Artifact | Status | Notes |
| --- | --- | --- |
| `2.1.3` GitHub Release asset | Supported as baseline | Re-hosts the exact upstream npm `@toast-ui/calendar@2.1.3` tarball. |
| New BlockGrain release assets | Supported when published | Security fixes should be released as new versions/assets rather than mutating the baseline. |
| Arbitrary branches or unbuilt source snapshots | Not supported for production consumption | Build and publish a release asset before use in AgriChain. |

## Reporting a Vulnerability

Report suspected vulnerabilities through BlockGrain's internal security/engineering process or by creating a private security advisory if repository permissions allow it.

Please include:

- affected package/artifact version
- affected product or workflow
- reproduction steps or proof of concept
- known impact and suggested mitigation, if available

## Maintenance Notes

- Preserve the MIT license and upstream copyright notices.
- Keep the upstream README content intact unless a change is required for BlockGrain maintenance notes.
- Validate release assets against the previous production dependency before switching AgriChain to a new artifact.
- Prefer new release versions for patches so existing lockfiles remain reproducible.
