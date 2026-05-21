# Kilonova · Founder OS · v1

Static HTML mockup of the Founder Interface — **v1 founder-first scope**.

Live: <https://founder-os-ui.vercel.app>
Archive (v0.9.x): <https://founder-os-ui-archive.vercel.app>

## v1 scope (founder-first, 4 surfaces + Settings)

This version follows Bruno's Product UI Roadmap v0.8 structure (audience + verb) but keeps our existing design system (V&T v0.7 · chartreuse focal-only · Source Serif · Helvetica · Space Mono · Phosphor Icons).

We're building the **Founder** audience first. Pilot and Prospect surfaces are out of scope for v1.

| # | Surface | State | Notes |
|---|---|---|---|
| 3 | **Reading** | Built | Brief inbox · default landing · 8 mock briefs · 5 type badges |
| 4 | **Approval** | Stub · Phase B | Decision packets · ratify / defer / send back |
| 5 | **Commitments** | Stub · Phase C | Promise ledger · drift alerts |
| 6 | **Status** | Stub · Phase D | Cockpit glance · 30-second view |
| – | **Settings** | Built (minimal) | Display · notifications · account |

### What's deliberately deferred to v2
- Voice memos as feedback primitive
- Surface 1 (24-phase cycle map) — full simplified version only when needed
- Surface 2 (out-of-app dual-track per pushback)
- Pilot surfaces (back-end operator)
- Prospect surface (public lead funnel)

## Shell
- **Header**: Logo · Client selector (Kilonova) · User dropdown (Gus Barta) · **Ask Kilonova** button (primary CTA, rightmost)
- **Left nav**: 64px icon-only with hover tooltips · Reading · Approval · Commitments · Status · Settings
- **Right rail**: Ask Kilonova chat (push panel, default closed, opens via header button — never overlaps content, grid resizes responsively)

## Design system (V&T v0.7)
- Background `#0a0a0a` (dark default) · light parity kept
- Accent `#DFFF00` chartreuse — **focal points only** (CTA, unread dots, decision badges, active nav indicator)
- Type: Source Serif 4 body · Helvetica Neue display · Space Mono mono
- Phosphor Icons throughout

## Reference docs
- `/Users/gusbarta/Documents/Kilonova OS/architecture-v0.md` (v0.6)
- `/Users/gusbarta/Documents/Kilonova OS/voice-and-tone-v0.md` (v0.7)
- `/Users/gusbarta/Documents/Kilonova OS/spec-avatar-system.md` (v0.1)
- `/Users/gusbarta/Documents/Kilonova OS/spec-ui-references.md` (v0.2)
- `/Users/gusbarta/Documents/Kilonova OS/spec-cockpit-references.md` (v0.1)
- `/Users/gusbarta/Downloads/spec_standalone.html` (Bruno's Product UI Roadmap v0.8)

## Build phases (founder-only)
- **Phase A** — Reading Surface ✅ shipped in v1.0
- **Phase B** — Approval Surface (next)
- **Phase C** — Commitments Surface
- **Phase D** — Status Surface
- **Phase E** — Editorial Page upgrade (direct-edit + comments + chat-with-content primitives)

## Deploy
GitHub `main` → Vercel auto-deploy (Kilonova team scope).
Stable URL: <https://founder-os-ui.vercel.app>
