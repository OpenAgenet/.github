# Contributing to OpenAgenet

Thank you for helping improve OpenAgenet.

## Contributor License Agreement

All external contributions must be covered by the OpenAgenet Contributor
License Agreement in `CLA.md`.

By opening a pull request, submitting a patch, or contributing code, tests,
documentation, design material, or assets, you confirm that you agree to the
CLA and have the right to contribute the submitted material.

This CLA-based process keeps the project able to:

- maintain open-source releases;
- use strong copyleft licenses for core service infrastructure;
- offer commercial or dual-license arrangements when appropriate;
- accept community contributions without blocking future governance options.

## License Awareness

Different repositories may use different licenses:

- core service and infrastructure code: usually `AGPL-3.0-only`;
- SDKs, adapters, plugins, deployment helpers, and developer tools: usually
  `Apache-2.0`;
- public documentation, specifications, and explanatory material: usually
  `CC-BY-4.0`;
- internal repositories: not open source unless explicitly relicensed.

Check each repository's `LICENSE` and `NOTICE.md` before contributing.

## Brand Use

OpenAgenet names, OAN names, logos, slogans, official-node labels, certified
labels, and endorsement language are not granted by code or documentation
licenses. See `TRADEMARKS.md` and `BRAND-GUIDELINES.md`.

## Tests

For OAN development preferences, follow `oan-design-docs/docs/project_skill.yml`
when available. In particular, prefer TypeScript integration and benchmark
tests, preserve existing coverage where possible, reuse genesis service-node
identity fixtures, and route full validation through
`oan-release-tools/scripts/run-full-regression.ts`.

