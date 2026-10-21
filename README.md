# The Table — Vandelay Travel

A multiplayer group-travel booking prototype: every trip gets a Table, everyone has a seat,
anyone can put an option on it, the group answers, and the app sets it.

Live: https://morrlunk.github.io/vandelay-table/

One self-contained HTML file. No build step, no backend, no dependencies beyond Google Fonts.
Open `index.html` and it runs.

## Disclosures

- **Vandelay Travel is a stand-in name.** The client is anonymised at their request, and the
  typography here is not theirs.
- **Emil, Anna and Dakota are simulated participants**, not real people.
- **Prices are illustrative.** There is no live inventory and nothing can be booked.
- **The assistant is a rule system over the table's own state, not a language model.**
  It derives every answer from the table. It infers nothing it does not show you.

## Accessibility

axe-core 4.10.2 across nine views, tagged for WCAG 2.0, 2.1 and 2.2 at A, AA and AAA:
0 violations, 29 passes. No tap target under 44 by 44, no text under 12 px, muted text at 7.3:1,
member colours distinguishable under deuteranopia.

Not covered by tooling and unverified by hand: VoiceOver reading order on a real iPhone,
Dynamic Type at its largest sizes, and the reduced-motion alternative for the seal.

---

Design and build by Matilda Orring Lunki · SnowBlizz Design
