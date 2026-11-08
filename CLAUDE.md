# Portfolio design standards

This is Kuzey Kantarcıoğlu's personal engineering and research website.

## Identity
The site is an editorial research notebook, not a SaaS landing page.
It should express technical rigor, experimental curiosity,
human personality, and exceptional attention to detail.

## Design
- Favor distinctive typography, original compositions, and restraint.
- Use consistent design tokens and a deliberate visual hierarchy.
- Treat whitespace, imagery, and motion as meaningful design tools.
- Avoid generic AI aesthetics, gratuitous gradients, glassmorphism,
  repetitive card grids, fake terminals, and pointless animations.
- Never add a visual effect merely to fill space.
- Make every page feel connected to the same design language.

## Content
- Technical achievements should be specific and verifiable.
- Separate completed work from ongoing research.
- Never fabricate metrics, publications, project media, or employers.
- Respect confidentiality and keep proprietary details private.
- Prioritize the quality of selected work over exhaustive listings.
- Write like a thoughtful engineer, not a marketing agency.

## Engineering
- Preserve working code and useful existing architecture.
- Avoid unnecessary libraries and abstractions.
- Build mobile-first, accessible, fast-loading interfaces.
- Support reduced motion and keyboard navigation.
- Test actual rendered pages, not just compilation.
- Refine visual details after every major implementation.

## Quality bar
Never stop at "it works."
Critique the result for originality, typography, spacing,
coherence, content quality, and genuine usability.
Fix visible shortcomings before reporting completion.

---

## Project context

- Stack: a single static `index.html` (inline CSS and JS, Google Fonts only), deployed with GitHub Pages from the `kuzeykantarcioglu.github.io` repo. Keep it static unless there is a strong reason to change.
- Links: github.com/kuzeykantarcioglu, linkedin.com/in/kkuzey, kuzey@stanford.edu. Resume PDF lives at `resume.pdf` in the repo root; only link it once the file exists.
- Unfinished details are marked with `<!-- TODO -->` comments. Leave them as comments; never render a placeholder link or empty button.

### Claims that need care
- Apple: the solver was designed to replace a lookup table; do not call it production-deployed. The ~500× figure is certification speed, not end-to-end solver runtime. Confirm public-disclosure approval before adding any further modem or hardware detail.
- Stanford robotics (FACT/YAM): live observation, inference, replay and evaluation are done. Do not claim a successful autonomous rollout, improved success rates, or validated intervention recovery.
- GPU inference and the CS329H supervisor-drift study are in progress. Show them as such, with no speedup or results until measured.
- Do not use: Microsoft's "92% accuracy", OBSS's "300% improvement", or the Koç paper as published, until each is defined or confirmed.
- NewFrame throughput and cost figures are from testing; say so.
- Team awards (TreeHacks, FIRST) are labeled as team awards.
