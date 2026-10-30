# DESIGN.md — Starship & Starlink Mission Control

## Point of view

This is an **ops wall** for a SpaceX-following household desk — glanceable T-minus, fleet counts, and theme cards — not a marketing landing page and not a trading terminal.

Reuses Design Motion Studio’s **ops-brief / IBM-ish clarity** intent (restrained system, no purple SaaS), adapted to a dark wall display.

## Palette (shipped UI)

| Token | Value | Role |
|-------|-------|------|
| `--bg` | `#0e1114` | wall / page |
| `--bg-elev` | `#161b21` | header / footer |
| `--panel` | `#1b222a` | cards |
| `--ink` | `#e8edf2` | primary text |
| `--muted` | `#8b97a5` | secondary |
| `--line` | `#2a3340` | borders / grid |
| `--amber` | `#e8a838` | T-minus / focus |
| `--cyan` | `#3db8c5` | LIVE badges / links |
| `--synth` | `#9aa3b0` | SYNTHETIC badges |

No purple primary. No neon mesh gradients in chrome. Subtle horizontal scan lines only (static CSS, no animation loop).

## Type

- UI: **IBM Plex Sans** (system-ui fallbacks)
- Mono: **IBM Plex Mono** for T-minus, clocks, source lines, section labels
- Display tracking slightly tight on the H1 (`-0.02em`)
- Tabular nums on countdowns

## Layout pattern

**Wall board:** top identity strip → four screen tabs → dense cards/metrics.  
Not hero → three feature cards. Not “✨ Introducing”.

Screens:

1. Countdown board (hero Falcon + Starship + grid)
2. Starlink overview (metrics → shells + recent lift)
3. News / theme strip
4. Why Parent A cares (SYNTHETIC notes)

## Motion

- Clock and T-minus refresh once per second (content update only).
- No infinite CSS animations, no `transition: all`, no scroll hijacks.
- `prefers-reduced-motion: reduce` kills any residual transitions.
- Tab buttons: color + underline only; `:active` not required for wall use.

## States

- Active tab underline in amber
- `:focus-visible` rings on tabs / skip link
- LIVE (cyan) vs SYNTHETIC (grey) tags on every card
- Past T-minus flips to muted `T+`

## Anti-patterns (this app)

- [ ] No Inter/Roboto as the only face
- [ ] No purple→blue gradients
- [ ] No ✨ Introducing pill
- [ ] No emoji logo (uses flat `MC` amber tile)
- [ ] No three equal marketing cards as the home layout
- [ ] Tokens live in `:root` before component paint
- [ ] No fake “live telemetry” without a LIVE tag + source URL

## Content voice

Plain ops English. Cite the source under the number. Prefer “NET Nov 8 (unofficial)” over “Launching soon!!!”.
