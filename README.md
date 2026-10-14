# Portfolio UI assets — Algolog own-products

In-app UI screenshots for four of Algolog's own products, for use on a freelancer portfolio. **All data shown is invented demo/seed data — no real customer records, no PII.** Final public wording/captions are Jake's call.

## How each set was produced (so captions stay honest)

| Product | Method | Data |
|---|---|---|
| **LuvStories** | **Live local app**, captured in-browser | Fake sample story / blank editor (no real users) |
| **Topschool** | **Live local app** on a freshly-seeded throwaway demo tenant | Invented school "Greenfield Model Academy," fake pupils (Ada Okon, etc.) |
| **SkillPay** | **Faithful static recreation** traced from the real frontend source (`app/u/[slug]/FunnelView.tsx`, `app/manage/dashboard`) | Invented creator "Zuri Beats," fake product/₦ amounts |
| **Spacer** | **Faithful static recreation** traced from the real frontend source (`app/mainpage/insight`, `app/[customUrl]/space/[id]`) | Invented operator "Harmattan Suites," fake rooms/guests/₦ |

> SkillPay and Spacer shots are **pixel-faithful rebuilds of screens that exist in the real codebase** (same layout, components, colors, copy), rendered from hand-authored demo data — not captures of the live production apps. Caption them as UI/product design work accordingly; don't present them as live production dashboards with real traffic.

## Folders
- `luvstories/` — animated story editor + tap-through viewer (desktop + mobile)
- `topschool/` — owner dashboard, pupils, results (grading), classes, attendance, report card (desktop + mobile)
- `skillpay/` — creator sales funnel (storefront) + creator dashboard
- `spacer/` — operator management dashboard + public booking page

## Honest results (if any numbers are cited on the profile)
- **LuvStories** is live; traction is small — cite exact figures or omit.
- **Topschool** is a live multi-tenant deployment; paying tenants are a small number (lead with the real one if citing).
- **SkillPay** / **Spacer** are live own-products; keep claims to capability, not inflated scale.

(Client case studies are handled separately and are consent-gated — not in this repo.)
