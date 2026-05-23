# graysond.xyz Public Portfolio Archive

Public portfolio archive for selected tools, research notes, field notes, and interactive source from [graysond.xyz](https://graysond.xyz/).

This repository is meant to show the public thinking and browser-local implementation behind the portfolio. It is a curated archive, not a full deployment mirror.

## Included

- `content/tools/` - public descriptions for the browser-local tools.
- `content/research/` - public research notes, field-note placeholders, and paper abstracts.
- `public/research/overlay-problem-crypto.pdf` - public research PDF already linked from the portfolio.
- `implementation/portfolio-tools-research.js` - the JavaScript source extract that powers the toolbench and research interactions on the portfolio.
- `implementation/portfolio-tools-research.css` - the CSS source extract for the tool and research UI.

## Tool Areas

- PromptPack Studio: reusable prompt templates with variables and standalone HTML export.
- Hash Inspector: local SHA digest generation.
- Passphrase Review: local passphrase shape checks.
- CIDR Inspector: IPv4 CIDR range decoding.
- Runbook Composer: practical checklist drafting for operational tasks.
- Probability Signal Simulator: conditional probability and decision-quality exhibit.
- Chaos Divergence Explorer: deterministic-system divergence visualization.

## Privacy Boundary

The tools are designed to run locally in the browser. User-entered tool inputs such as prompts, passphrases, hashes, CIDR values, and runbook notes should not be transmitted to third-party services.

## Non-Advice Notice

Market, crypto, probability, and research material here is portfolio context only. It is not investment, trading, financial, tax, legal, compliance, cybersecurity, or operational advice.

## Repository Boundary

This public package intentionally excludes:

- Cloudflare deployment config and tokens.
- Local QA screenshots.
- Generated `dist/` assets.
- Local agent/operator docs.
- Employer-specific operational details.
- Private implementation notes not intended for public readers.

## License

No open-source license is granted by default. See `LICENSE.md` and `NOTICE.md`.
