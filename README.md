# Portfolio UI assets

In-app UI screenshots for a freelancer portfolio. **All data shown is invented demo/seed data — no real customer records, no PII.** Final public wording/captions are Jake's call.

## A. Algolog own-products

| Product | Method | Data |
|---|---|---|
| **LuvStories** | **Live local app**, captured in-browser | Fake sample story / blank editor (no real users) |
| **Topschool** | **Live local app** on a freshly-seeded throwaway demo tenant | Invented school "Greenfield Model Academy," fake pupils (Ada Okon, etc.) |
| **SkillPay** | **Faithful static recreation** traced from the real frontend source (`app/u/[slug]/FunnelView.tsx`, `app/manage/dashboard`) | Invented creator "Zuri Beats," fake product/₦ amounts |
| **Spacer** | **Faithful static recreation** traced from the real frontend source (`app/mainpage/insight`, `app/[customUrl]/space/[id]`) | Invented operator "Harmattan Suites," fake rooms/guests/₦ |

Folders: `luvstories/`, `topschool/`, `skillpay/`, `spacer/`.

## B. Client builds — ANONYMIZED

These are **faithful, fully anonymized recreations of bespoke client software**, traced pixel-for-pixel from the real codebases and rendered on hand-authored demo data. Every client identity has been stripped — generic placeholder brand, no real client/brand name, location, person, domain, or distinguishing content. Used with the business owner's sign-off.

| Build | Shown as | What it is |
|---|---|---|
| **Learning platform** | "Meridian Learning" (placeholder) | A professional-development LMS: course/lesson player, learner dashboard, programs, live sessions, certificates |
| **Laundry operations** | "CrispFold" (placeholder) | A multi-branch laundry/dry-clean ops system: front-desk POS intake (pay-before-release), per-garment UHF-RFID tracking, factory station flow, piece-rate presser count |

Folders: `client-lms/`, `client-laundry/`.

## How to caption honestly
- **Live captures** (LuvStories, Topschool): in-app screenshots on seeded demo data.
- **Recreations** (SkillPay, Spacer, both client builds): pixel-faithful rebuilds of screens that exist in the real codebase, rendered from invented demo data — caption as **UI / product-design work**, not as live production dashboards with real traffic or real users.
- **Client builds**: present only as anonymized/representative work; do not name or hint at the real client.

## Numbers discipline (if any figures are cited)
- **LuvStories** is live; traction is small — cite exact figures or omit.
- **Topschool** is a live multi-tenant deployment; paying tenants are a small number.
- **SkillPay / Spacer / client builds**: keep claims to capability, not inflated scale.
