# Learning Code — Project Instructions

## Brand

All HTML pages in this directory use the Max Steel visual identity system. Before creating or editing any `.html` file, read `brand-agent.md` in full.

The brand agent defines:
- Color tokens (`--turbo-black`, `--turbo-electric`, `--turbo-yellow`, `--turbo-purple`, etc.)
- Font stack and typography hierarchy (wide/heavy display vs. condensed technical text)
- Motion tokens and animation rules
- Voice and copy rules (hype/kinetic, not military-technical)
- Component decision tree
- Anti-patterns to avoid
- **Mandatory creator portrait** — `local branding assets/cute picture of me.png` must appear on every page (see Section 6 of brand-agent.md for placement rules)

Never introduce a color, typeface, spacing value, or copy pattern that is not defined in `brand-agent.md`.

## File conventions

- One HTML file per page — no frameworks, no build tools
- CSS lives in a `<style>` block in the same file unless a shared stylesheet is explicitly set up
- Canvas-based decorative graphics only (no hand-authored SVG path data)
- `prefers-reduced-motion` must be respected in every file that uses animation
