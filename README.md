# sig.proof.sh

Proof email signature assets, hosted via GitHub Pages at [sig.proof.sh](https://sig.proof.sh).

## What's here

- `front_default.html` -- the main email signature template for Front (uses `{{user.name}}`, `{{user.custom.title}}`, etc.)
- `proof_full_color_sig.png` -- current Proof logo used by the signature (107×72 source, rendered at 53×36)
- `proof_full_color-{sm,md,lg}.webp` -- WebP variants of the Proof logo
- Legacy `pg-*` / `P+g_*` / `pg_logo_*` assets from the Proof+Geist era (kept so any pre-rebrand signatures already cached in email clients continue to resolve; don't link to them in new templates)

## Editing the signature

Edit `front_default.html`. Changes go live on push to main (GitHub Pages, hosted at `sig.proof.sh`).

The template uses Front's variable syntax so each team member gets their name and title automatically.

## Design rules

- Logo appears first in the signature
- Logo height: 36px (current logo aspect ratio is 1.48:1 → 53px wide at 36px tall)
- Use the PNG served from `https://sig.proof.sh/` (not the WebP, for broader email-client compatibility — Outlook desktop in particular is spotty on WebP)
- Canonical logo source lives in the sibling repo `../proof-marketing-assets/Full Logo/Full Color_Logo.svg`; regenerate the PNG from that SVG if you need to resize

