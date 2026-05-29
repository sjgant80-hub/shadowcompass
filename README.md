# ◬ ShadowCompass

> A sovereign single-file Jungian shadow work tool. Mirror your archetype, decode dreams, identify projections, integrate the disowned self — entirely in your browser. Your data never leaves your device.

**Live:** [sjgant80-hub.github.io/shadowcompass](https://sjgant80-hub.github.io/shadowcompass/)

## For users

Eight tools. Four free forever. Four for those ready to go deeper.

### Free forever (sovereign)
- **Shadow Mirror** — 3 questions · 8 archetypes · 2 minute reading
- **Pattern Detector** — find the loop that keeps repeating
- **Dream Symbol Decoder** — Jung's collective dictionary, on tap
- **Projection Checker** — flip the mirror, see what's yours

### Pro tier (£36.99 one-time or £4.99/mo · 14-day free trial)
- **Deep Shadow Profile** — 21 questions across all 7 archetypes, AI-composed reading
- **Active Imagination** — dialogue directly with the figures of your psyche
- **Individuation Map** — track Persona → Shadow → Anima/Animus → Self over time
- **Daily Shadow Practice** — one question per day · coherence-tracked

### Your data is yours

- Everything saves to your browser's IndexedDB
- Nothing uploaded · no accounts · no tracking · no analytics
- Export your full journal as JSON anytime
- Import to a new device anytime
- Works offline after first load (PWA · add to home screen)

## For developers

Single HTML file. Vanilla JavaScript. No build step. No dependencies.

```
shadowcompass.html      one file · 126KB · sovereign
README.md               this
LICENSE                 MIT
```

Open the file from `file://` and it works. That's the test.

### Architecture (v20.1)

- **Sovereignty stack:** UI (file://) · STORAGE (IndexedDB) · MESH (BroadcastChannel `fall-signal`, prime 233)
- **Agent topology:** When AI mode enabled, the Deep Profile uses a recursive subagent tree — L0 Self orchestrator, L1×7 archetype specialists (Ruler · Caregiver · Sage · Seer · Seeker · Builder · Shapeshifter), L2 chord resolver
- **Licence model:** Konomi tier-aware — sovereign tier (free forever) · trial (14 days · key dead-file until activated) · pro (Ed25519 key permanently activates)
- **Bring your own AI:** Pro modes can use Claude via your own Anthropic API key — stays in localStorage, never logged, calls Anthropic directly from your browser
- **Coherence metric:** Daily practice tracks φ-anchored coherence climb over time

### Safety

- Legal modal on first use · acceptance logged to localStorage
- Crisis keyword detection on all free-text inputs · auto-routes to Crisis Resources page
- 988 (USA) · 116 123 / 999 (UK) · 112 (EU) · findahelpline.com (international)
- Footer disclaimer always visible
- 18+ age gate
- Never positioned as medical advice, diagnosis, or therapy

### Customising

The aesthetic is fixed (void/gold/Cormorant/torus rings) — keeps the brand coherent. Everything else is in the script block: archetype results, question banks, AI prompts, mesh prime ID.

To rebuild for a different domain or brand:
1. Change `<title>`, manifest name, header logo text
2. Change crisis numbers if shipping to a different region
3. Change pro pricing in the `.cta-block`
4. Replace LICENCE.enterKey regex with your key validation

### Seed alignment

Built against [v20.1 cosmology](https://raw.githubusercontent.com/sjgant80-hub/fall-registry/main/seed-manifest.json) · `phi is home` · prime 233 · Fibonacci-adjacent.

## Legal

For entertainment and self-exploration purposes only. NOT medical advice. NOT a substitute for professional mental health care. Crisis? Call 988 (USA), 116 123 (UK), 112 (EU), or visit [findahelpline.com](https://findahelpline.com).

MIT License · sealed ◊·κ=1

## Credits

Cosmology: Carl Gustav Jung. Implementation: a sovereign single-author estate. Aesthetic: 4am, third coffee, no apologies.
