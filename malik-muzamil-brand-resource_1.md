# 🧠 MALIK MUZAMIL — MASTER BRAND RESOURCE FILE v3.0
> **Purpose:** Source of truth for the Growlioo website rebuild. This file replaces v2.0.
> **Brand:** Growlioo | **Founder:** Malik Muzamil
> **Last Updated:** July 2026
> **v3.0 Changes:** New offer ladder (LinkedAI $495 RETIRED, Foundation/Growth RETIRED). New 4-page architecture: Homepage (high-ticket only) · /inbound · /allbound · /offers. Outcome-based offer names. New lead magnet routing into the Inbound offer. Design system unchanged from v2.0.

---

## 📌 TABLE OF CONTENTS
1. [Website Architecture v3](#1-website-architecture-v3)
2. [The Offer Ladder (all offers, canonical)](#2-the-offer-ladder)
3. [Design System (unchanged)](#3-design-system)
4. [Homepage Copy Spec](#4-homepage-copy-spec)
5. [/inbound Page Copy Spec](#5-inbound-page-copy-spec)
6. [/allbound Page Copy Spec](#6-allbound-page-copy-spec)
7. [/offers Page Copy Spec](#7-offers-page-copy-spec)
8. [Lead Magnet Spec](#8-lead-magnet-spec)
9. [Redirects & Retired Assets](#9-redirects--retired-assets)
10. [Brand Identity, Bio, ICP, Case Studies, Testimonials, Objections, CTAs, Contact](#10-carried-over-sections)
11. [Claude Code Build Notes](#11-claude-code-build-notes)

---

## 1. WEBSITE ARCHITECTURE v3

### The Model
The public website leads with HIGH TICKET ONLY. Low-ticket and middle-ticket offers are never mentioned on the homepage, /inbound, or /allbound except through one neutral link: **"See All Our Systems →" → /offers**. Low/middle offers each get their own dedicated landing pages LATER (promoted separately via posts, DMs, ads). For now, /offers is the single hub listing everything.

### Site Map
```
/            → Homepage. High-ticket only: Inbound + Allbound cards. Lead magnet section. "See All Our Systems" band.
/inbound     → The LinkedIn Inbound Install — $997/mo (price PUBLIC on this page)
/allbound    → The LinkedIn Allbound System — call/DM only, "starts at $1,997/mo" softness
/offers      → ALL offers on one scroll (low → high). Each card has a button that will later
               point to its own dedicated landing page (wire buttons now, real URLs later).
```
No /case-studies page. Case studies are embedded as sections inside the pages. No /linkedai page. No /done-for-you page (301s below).

### Navigation (top bar)
`Home · Inbound Install · Allbound System · All Systems` + pill button: **Get in Touch**

### Conversion Logic
- Homepage hero = category-level promise. Two offer cards = **Inbound Install (light card)** and **Allbound System (dark card, premium)**. Nothing cheaper is named on the homepage.
- Below the cards, one slim cream band: *"Not ready for done-for-you? We have systems from $17. → See All Our Systems"* → /offers. This is the ONLY low-ticket reference on the homepage.
- Lead magnet (Section 8) opt-in routes the subscriber INTO the Inbound offer: thank-you page + first email both point to /inbound and its deliverables.
- /inbound shows its price ($997/mo). /allbound never shows a hard price on a card — "starts at $1,997/mo" appears once in FAQ copy; CTA is Book a Call / DM.
- Cross-links: /inbound → "Want outbound running daily too? → Allbound". /allbound → "Want inbound only? → Inbound Install". Both → slim "See All Our Systems" band near the footer.
- /offers is the ladder hub: every offer card, cheapest first, each with its own CTA button (wired later to dedicated landing pages / checkout).

---

## 2. THE OFFER LADDER (canonical — use these names, outcomes, and prices everywhere)

| # | Offer | Price | Type | Outcome line | Page/CTA |
|---|---|---|---|---|---|
| 1 | **LinkedAI Starter Plugin** | $17 one-time | DIY digital | Your first 100K impressions + first 10 clients from LinkedIn | /offers card → future landing page (wire button) |
| 2 | **The Client-Getter Vault** | $47 add-on | DIY bundle (order bump) | Turn views into buyers, faster | Sold at Starter checkout only; listed on /offers |
| 3 | **Lead Magnet Machine** | $97 | DWY system | The system behind 1M+ impressions & 1000s of leads | /offers card → future landing page |
| 4 | **Inbound Content Engine** | $147 | DWY system | Consistent inbound leads from LinkedIn every single week | /offers card → future landing page |
| 5 | **DM-to-Booked-Calls System** | $197 | DWY system | 10+ qualified leads from LinkedIn every week | /offers card → future landing page |
| 6 | **The LinkedIn Client Stack** | $297 (all 3 systems, save $144) | DWY bundle | Every system that gets clients from LinkedIn — in one stack | /offers featured card |
| 7 | **The LinkedIn Inbound Install** | **$997/mo** (public) · 90-day min | DFY retainer | Consistent inbound inquiries without writing a single post yourself | /inbound |
| 8 | **The LinkedIn Allbound System** | Starts at $1,997/mo (call/DM only) · 90-day min | DFY retainer | Inbound + outbound running daily — 10+ qualified conversations booked every week | /allbound |

**Retired:** LinkedAI System $495 · Foundation package · Growth package · the old 3-service menu. Never render these names or the $495/$295 price anywhere.

### Full Deliverables (canonical)

**LinkedAI Starter Plugin — $17**
- Plug-and-play Claude plugin: post writer + hook generator skills
- The exact AI system behind 100K impressions for clients
- 10-minute install + quick-start video

**The Client-Getter Vault — $47** (order bump)
- Advanced skills: carousels, cheatsheets, comment writer
- Profile optimizer add-on
- Swipe files + plug-and-run templates

**Lead Magnet Machine — $97**
- Lead magnet builder plugin · Top-50 proven lead magnet swipe file · Delivery DM templates
- Proof: 1M+ impressions & thousands of leads generated for clients

**Inbound Content Engine — $147**
- 30-day content system plugin · Video masterclass (content → inbound leads) · Posting cadence templates

**DM-to-Booked-Calls System — $197**
- Outreach plugin (voice-note flow) · The DM playbook behind $50K+ closed · Follow-up + reactivation sequences

**The LinkedIn Client Stack — $297** = all three systems above (anchor: $441 value, save $144).

**The LinkedIn Inbound Install — $997/mo**
- Profile revamp + positioning (ICP, positioning statement, messaging pillars, banned-words list)
- Monthly content strategy + daily posts written, designed & published for you (16–20 posts/month, your voice, you approve)
- Lead magnet system installed & run
- 1 strategy call / month
- Early Joiner Bonus: free 1:1 90-Day Content Roadmap Call (normally $300)
- 90-day minimum

**The LinkedIn Allbound System — starts at $1,997/mo**
- Everything in the Inbound Install, plus:
- Dedicated account manager, 3–4 hrs daily on your account
- Daily engagement: 30–50 strategic comments/day inside your industry
- Daily outreach at higher volume: lead lists, connection requests, strategic DMs
- KPI tracking: weekly + monthly performance reports (impressions, followers, engagement, outreach results)
- Bi-monthly strategy calls
- Early Joiner Bonus: 6-Hour Emergency Content Slot
- Sold by application: Book a Free Strategy Call / DM only · 90-day minimum

---

## 3. DESIGN SYSTEM (UNCHANGED from v2.0 — restated for the build)

**LIGHT-FIRST SITE.** White + cream `#FAF0E6` alternating sections, Shoaib Ahmed layout structure. Dark `#1A1A1A` in exactly these money-moments: (1) homepage results band, (2) the **Allbound card** (was Growth card) on homepage and the Allbound package card, (3) the footer, (4) one dark pricing/summary card allowed per subpage. No full-dark pages.

### Color Tokens
| Token | Hex | Usage |
|---|---|---|
| `--orange` | `#F47B20` | Primary CTAs, headline accent words, stat numbers, icons, links, checkmarks |
| `--orange-hover` | `#D9660F` | Button hovers |
| `--cream` | `#FAF0E6` | Light section backgrounds (alternate with white) |
| `--dark` | `#1A1A1A` | Body text on light; dark sections |
| `--near-black` | `#0D0D0D` | Footer / dark card gradients |
| `--white` | `#FFFFFF` | Light sections, text on dark |
| `--orange-glow` | `rgba(244,123,32,0.15)` | Glow behind dark cards |

Orange rules: accent words inside dark headlines; solid orange buttons with WHITE text; thin orange card borders; orange pill eyebrows or 8% tint fills; max ONE full-orange band per page; orange check icons; stat numbers oversized in orange with small grey labels.

Typography: bold geometric sans (Inter/Figtree class), tight tracking; body 16–18px `#1A1A1A` on light.

Components (already built — reuse): floating testimonial hero cards, star/avatar trust strip, stat trio blocks, before/after table (dark-orange right column), numbered 01–04 rows, case-study feature cards, dark card with orange glow + checklist, 3-step Enquire→Onboarding→Execution, FAQ accordion.

---

## 4. HOMEPAGE COPY SPEC ( / )

Keep the existing built homepage structure and design. Content changes only where marked.

### Hero (unchanged layout: floating stat chips + photo)
**Eyebrow:** For founders, executives and consultants.
**Headline:** Turn your LinkedIn into an **inbound revenue machine.** *(orange accents — unchanged)*
**Sub (UPDATED):** Your entire LinkedIn presence — content, engagement, and outreach — fully handled by us. You show up as the authority. Your pipeline fills with qualified conversations.
**CTAs (UPDATED):**
- `Explore the Inbound Install` (orange, primary → /inbound)
- `Explore the Allbound System` (outline, secondary → /allbound)
**Trust strip:** ★★★★★ avatars + "2M+ impressions generated for clients · 50+ founders served across 6 industries"

### Section: Trusted By / Proof Bar (dark band — unchanged)
Daniel Paul pull quote + logo strip. No changes.

### Section: Here's How We Can Work Together (2 cards — UPDATED, core change)
**Card 1 — The LinkedIn Inbound Install** *(light/cream card, orange headings)*
Tag: `Done-For-You · $997/mo`
> Consistent inbound inquiries without writing a single post yourself. Profile revamp, monthly strategy, daily posts written and published for you, lead magnet system installed and run.
Button: `Explore the Inbound Install →` → /inbound

**Card 2 — The LinkedIn Allbound System** *(dark #1A1A1A card, orange glow — premium signal)*
Tag: `Done-For-You · Inbound + Outbound`
> Inbound + outbound running daily — 10+ qualified conversations booked every week. Everything in the Inbound Install plus a dedicated account manager engaging and reaching out for you, every day.
Button: `Explore the Allbound System →` → /allbound

**Slim band directly under the cards (cream, small text — the ONLY low-ticket reference on this page):**
*"Not ready for done-for-you? We have DIY and done-with-you systems from $17."* `See All Our Systems →` → /offers

### Section: I Help You... (3 cards — unchanged)
Visibility. Authority. Revenue. (keep existing copy)

### Section: Results (dark band — unchanged)
Keep existing stat set (700K+, 5K+, 10+, 1,000+) and scrolling proof ticker.

### Section: Case Study Feature Blocks (keep — absorbs the retired /case-studies page)
All 3 full case studies from Section 10 (Daniel Paul, Mehsum Sayani, Muhammad Usman) in feature-block layout.

### Section: Free Lead Magnet (UPDATED — see Section 8)
**Headline:** Steal the exact system behind our clients' inbound pipelines.
**Sub:** The LinkedIn Inbound Blueprint — the 90-day system we install for clients at $997/mo, mapped out free. See every deliverable, every step, and why it works.
Form: Name + Email. Button: `Send Me the Blueprint →`
(Thank-you + email #1 route to /inbound.)

### Section: About Malik (unchanged) · Testimonial Wall (unchanged) · FAQ (update any answer that referenced $495/Foundation/Growth)

### Final CTA (dark band — UPDATED buttons)
**Headline:** Ready to turn LinkedIn into your #1 client source?
Buttons: `Explore the Inbound Install` + `Book a Strategy Call`

---

## 5. /INBOUND PAGE COPY SPEC — The LinkedIn Inbound Install · $997/mo (price PUBLIC)

Light theme. One dark pricing card with orange glow allowed.

### Hero
**Eyebrow:** For founders who are done writing their own posts.
**Headline:** Consistent inbound inquiries. **Without writing a single post yourself.**
**Sub:** We revamp your profile, plan your strategy, and write, design, and publish your content daily — with a lead magnet system running underneath. You approve. We handle everything else.
**CTA:** `Book a Free Strategy Call` (orange) · secondary text link: `See exactly what's included ↓`
**Stat chips:** `461K impressions in 90 days` · `10+ qualified leads/mo` · `16–20 posts/mo done for you`

### Section: This Is For You If... (6-grid, reuse component)
Growth flattened despite real expertise · Wasting hours on content that isn't converting · Competitors dominate a space you know better · Relying on referrals and unpredictable outbound · Zero time to write, design, engage daily · Best-kept secret in your industry.

### Section: Before / After table (reuse component, dark-orange right column)
Posting endlessly without results → Content engineered for inbound · Invisible despite expertise → Recognized authority · Referral-dependent pipeline → Consistent inbound inquiries · No strategy → Monthly calendar tied to revenue goals · Views that go nowhere → A profile that converts visitors to calls.

### Section: What's Included (numbered 01–05 rows)
01 **Profile Revamp + Positioning** — ICP, positioning statement, messaging pillars, banned-words list, full profile rewrite (headline, About, banner, featured, experience).
02 **Monthly Content Strategy** — first month fully planned: hooks, angles, topics mapped to your ICP's actual pain points.
03 **16–20 Posts & Designs / Month** — written in your voice: text, image posts, carousels, infographics. You approve. We publish daily.
04 **Lead Magnet System, Installed & Run** — the same engine behind 1,000+ leads from lead magnets for clients.
05 **1 Strategy Call / Month** — direction, review, and the numbers.

### Section: Pricing Card (dark card, orange glow)
**$997/mo** · 90-day minimum · full checklist of the five rows above · Early Joiner Bonus strip: *Free 1:1 90-Day Content Roadmap Call (normally $300)* · CTA `Book a Free Strategy Call`
Small print: Results vary by niche, offer, and consistency.

### Section: Case Studies (embed 2)
Daniel Paul (461K/90 days, workshops selling through LinkedIn) + Muhammad Usman (10+ qualified leads/month, LinkedIn = #1 lead source), feature-block layout + analytics screenshots.

### Section: Your Next Steps (3-step) · Testimonials · FAQ
FAQ additions: "Why $997 when others charge $2–3K?" / "How much of my time does this take?" (≈30 min/week approvals) / "How soon do leads show up?" / "Do you need my LinkedIn password?"

### Cross-sell bands
Upper (after pricing): *"Want engagement and outreach running daily on top of this? → The Allbound System"* → /allbound
Footer band: *"Prefer to run it yourself? We have systems from $17. → See All Our Systems"* → /offers

### Final CTA
**Headline:** Your pipeline shouldn't depend on you posting today.
CTA: `Book Your Free Strategy Call →`

---

## 6. /ALLBOUND PAGE COPY SPEC — The LinkedIn Allbound System · call/DM only

Light theme. The package/summary card on this page is the dark premium card.

### Hero
**Eyebrow:** For founders who want the whole pipeline run for them.
**Headline:** Inbound + outbound, running daily. **10+ qualified conversations booked every week.**
**Sub (defines "allbound" in one line):** Allbound = your content pulling buyers in while a dedicated account manager pushes outreach and engagement out — both, every single day, done for you.
**CTA:** `Book a Free Strategy Call` · secondary: `DM "ALLBOUND" on LinkedIn`
**Stat chips:** `1.5M impressions in 60 days` · `$40–50M contracts influenced` · `30–50 comments/day for you`

### Section: This Is For You If... (6-grid)
You want conversations, not just content · Your calendar should fill without you prospecting · You've outgrown referrals · You want one team owning the whole channel · You value time over money · You're scaling and can handle 10+ conversations/week.

### Section: What's Included (dark premium card + numbered rows)
**Everything in the Inbound Install** (link the five rows) **plus:**
01 **Dedicated Account Manager** — one operator, 3–4 hours daily on your account. Knows your voice, niche, goals.
02 **Daily Engagement** — 30–50 strategic comments/day inside your industry; you become the person worth following before they ever hit your profile.
03 **Daily Outreach, Higher Volume** — lead lists built, connection requests, strategic DMs every day.
04 **Weekly + Monthly Reports** — impressions, follower growth, engagement rate, outreach results. You always know the return.
05 **Bi-Monthly Strategy Calls.**
Early Joiner Bonus: *6-Hour Emergency Content Slot* — press feature or big announcement live within 6 hours.
**No price on the card.** CTA: `Book a Free Strategy Call`. FAQ contains the only price line: *"Allbound engagements start at $1,997/mo with a 90-day minimum — final scope is set on the call."*

### Section: Case Study (embed 1, full)
Mehsum Sayani — 1.53M impressions in 60 days, +4,421%, $40–50M in government contracts. This is THE allbound proof story.

### Section: Before/After · 3 Steps · Testimonials · FAQ
FAQ: What's the difference vs Inbound Install? / Who does the outreach and does it sound like me? / How do you measure it? / Why is there no price on this page? / How fast can you start?

### Cross-sell bands
*"Only need the inbound side handled? → The Inbound Install ($997/mo)"* → /inbound
Footer band: *"See every system we offer, from $17 up. → See All Our Systems"* → /offers

### Final CTA
**Headline:** Ready to become impossible to ignore?
CTA: `Book Your Free Strategy Call →`

---

## 7. /OFFERS PAGE COPY SPEC — All Our Systems (the ladder hub)

Light theme, cream/white alternating. Cheapest → biggest, one scroll. Every card gets a CTA button; low/middle buttons are WIRED PLACEHOLDERS for now (each will later point to its own dedicated landing page — use `href="#"` with `data-offer` attributes so links are swappable in one place).

### Hero
**Eyebrow:** Every Growlioo system, one page.
**Headline:** Pick your speed. **Same destination: clients from LinkedIn.**
**Sub:** DIY plugins from $17. Done-with-you systems from $97. Or hand us the keys and we run everything. Every tier is built on the same engine behind 2M+ client impressions.

### Tier 1 band — Do It Yourself (white)
**Card: LinkedAI Starter Plugin — $17 one-time**
Outcome: Your first 100K impressions + first 10 clients from LinkedIn.
Bullets: plug-and-play Claude plugin (post writer + hooks) · the exact system behind 100K impressions · 10-min install + quick-start video.
Button: `Get the Starter Plugin — $17 →` *(placeholder link)*
Small note on card: *At checkout: add The Client-Getter Vault ($47) — advanced skills, profile optimizer, swipe files & templates.*

### Tier 2 band — Done With You: The Growth Systems (cream)
Three cards side by side:
- **Lead Magnet Machine — $97** · Outcome: the system behind 1M+ impressions & 1000s of leads · bullets per Section 2 · `Get the Machine →`
- **Inbound Content Engine — $147** · Outcome: consistent inbound leads every single week · bullets · `Get the Engine →`
- **DM-to-Booked-Calls System — $197** · Outcome: 10+ qualified leads from LinkedIn every week · bullets · `Get the System →`
**Featured bundle card (orange thin border, 8% tint):** **The LinkedIn Client Stack — all 3 for $297** (value $441 — save $144). Button: `Get the Client Stack — $297 →` *(placeholder link)*

### Tier 3 band — Done For You (white; Inbound light card + Allbound dark card side by side, reuse package-card components)
- **The LinkedIn Inbound Install — $997/mo** · outcome line · 5 key deliverables · `Explore the Inbound Install →` → /inbound
- **The LinkedIn Allbound System — by application** · outcome line · "Everything in Inbound plus dedicated manager, daily engagement + outreach, reports" · `Explore the Allbound System →` → /allbound

### Section: Which one is right for me? (simple 3-column pointer)
"I'll run it myself" → Starter Plugin · "I want the systems + guidance" → Client Stack · "I want it fully handled" → Inbound / Allbound.

### Section: mini-FAQ + Final CTA
FAQ: What's the difference between DIY and DWY? / Can I upgrade later and get credit? (yes — Stack buyers get $297 credited against their first Inbound month) / What do I need to run the plugins? (a Claude subscription, ~$20/mo).
Final CTA band: `Not sure? Book a free strategy call →`

---

## 8. LEAD MAGNET SPEC (NEW)

**Name:** The LinkedIn Inbound Blueprint
**Format:** Free training/PDF — the exact 90-day inbound system Growlioo installs for clients at $997/mo, fully mapped: every deliverable, the posting cadence, the lead magnet engine, and the KPI targets.
**Why this asset:** It is a free preview OF the Inbound Install. Anyone who consumes it has effectively read the /inbound sales page in value-first form.
**Placement:** Homepage lead magnet section + top-bar link optional + exit intent (optional, Marie pattern).
**Routing (the "new opening"):**
1. Opt-in form (name + email) →
2. Thank-you page: "Your Blueprint is in your inbox. Want us to install all of this for you? → Explore the Inbound Install ($997/mo)" →
3. Email #1 delivers the Blueprint + links to /inbound →
4. Emails #2–4 (pre-purchase rail) walk through Blueprint highlights, case studies (Usman, Daniel), and end on the strategy-call CTA.
All lead magnet CTAs and copy reference INBOUND deliverables only — never low-ticket, never Allbound (Allbound is introduced on the call or on /inbound's cross-sell).

---

## 9. REDIRECTS & RETIRED ASSETS

**Page transformation map (1-to-1 — each old page becomes one new page):**
| Old page | Becomes | Redirect |
|---|---|---|
| `/` (homepage) | `/` — stays, copy-only changes | none needed |
| `/linkedai` | `/inbound` (UI kept, copy swapped) | `/linkedai` → 301 → `/inbound` |
| `/done-for-you` | `/allbound` (UI kept, copy swapped) | `/done-for-you` → 301 → `/allbound` |
| `/case-studies` | `/offers` (page slot reused; case-study content moves into homepage + /inbound + /allbound sections) | `/case-studies` → 301 → `/offers` |

- Global purge: `$495`, `$295`, "LinkedAI System" (as a $495 offer), "Foundation", "Growth" (as package names), the old 3-service menu. The word "LinkedAI" survives ONLY inside "LinkedAI Starter Plugin" ($17).

---

## 10. CARRIED-OVER SECTIONS (unchanged from v2.0 — keep verbatim)
The following v2.0 sections remain the canonical source and are carried over without change. Claude Code: reuse them exactly as previously implemented.
- **Brand Identity & Positioning** (name, mission, voice, colors, crown wordmark)
- **Founder Bio & Story** (short / medium / long bios, roles, education, Islamabad)
- **Target Audience (ICP)** — update the offer→ICP table: $17–$297 offers = hands-on solo founders/consultants; $997 Inbound = established founders who value time; Allbound = funded/scaling founders & execs.
- **Client Case Studies** — Daniel Paul (461,838 impressions / +242.3% / 21,607 followers / 125,314 top post), Mehsum Sayani (1,533,600 impressions / +4,421% / $40–50M contracts / Top 1% reach), Muhammad Usman (10+ qualified leads/mo / #1 inbound source / +43.1% impressions). Full tables and quotes as in v2.0.
- **Testimonials** (Tatiana Latartseva, Shehzadi Rabia, ETCHIFY founder, Akash Parvez, Abdul Haseeb, Smriti Maan)
- **Social Proof stat bank** (2M+ impressions · 1.5M/60 days · +260% · +4,421% · 10+ leads/mo · $40–50M · 50+ founders / 6 industries)
- **Objection Handling** — update two answers: replace the "$495" objection with *"Why is the Inbound Install $997 when agencies charge $2–3K?"* (answer: productized system, no bloated retainer, 90-day minimum keeps us accountable) and add *"What does 'Allbound' mean?"* (answer: inbound content pulling buyers in + daily outbound engagement/outreach pushing out — one team, both directions).
- **CTAs:** Inbound → `Book a Free Strategy Call →` · Allbound → `Book a Free Strategy Call →` / `DM "ALLBOUND"` · Offers page low-ticket → `Get the [name] — $X →`
- **Contact Information** (phone, email, LinkedIn, Islamabad)

---

## 11. CLAUDE CODE BUILD NOTES
1. **Do not redesign.** The three existing pages (home, old LinkedAI page, old DFY page) carry the correct design system. This is a content-architecture refactor: restructure, rename, rewire. **The homepage layout is FROZEN — copy-only changes.** Every section keeps its exact structure, spacing, components, and visual rhythm; only text, tags, and link targets change where Section 4 says so.
2. **Transform map (UI-preserving):**
   - Old `/linkedai` page → **becomes `/inbound`**. Keep the entire page UI intact section by section (hero + floating cards, stat chip strip, pain cards, orange promise band, numbered rows, checklist card, value-stack section, screenshots section, dark pricing card with orange glow, FAQ, final band). Swap copy per Section 5: hero → Inbound Install promise; stat chips → Inbound stats; numbered rows → the 5 Inbound deliverables; orange band → "Your entire LinkedIn, handled — live in 30 days"; value-stack table → "A ghostwriter $1,500+/mo · engagement manager $800+/mo · outreach VA $600+/mo → Inbound Install: $997/mo, one team"; dark pricing card → **$997/mo**, 90-day minimum, Early Joiner Bonus strip. Where a section genuinely doesn't map (e.g., "$20/mo to run" chip), replace its content with the nearest Inbound equivalent — never delete the section's UI.
   - Old `/done-for-you` page → **becomes `/allbound`**. Keep its UI (this-is-for-you grid, before/after table, package cards, case-study blocks, 3-step, FAQ). The dark Growth card becomes the Allbound premium card (Section 6); the light Foundation card is removed from this page and its component is reused on `/offers` for the Inbound card.
   - Old `/case-studies` page → **becomes `/offers`** (the page slot/route is reused). Assemble it from existing components only (offer cards, checklists, stat chips, FAQ accordion) per Section 7. Its case-study content is not lost — the full case studies already live as embedded sections on the homepage, /inbound, and /allbound. No new component designs.
3. Homepage: only the two offer cards, their tags/copy/links, the slim "See All Our Systems" band, the lead magnet section copy, hero sub + CTA labels, and final CTA buttons change. Everything else stays. **Zero layout, spacing, or component changes on the homepage.**
4. Dark usage stays sanctioned: homepage results band + proof bar, Allbound dark cards, one dark pricing card per subpage, footer.
5. All stat numbers oversized orange with small grey labels (existing pattern).
6. Low/middle-ticket buttons on /offers: `href="#"` + `data-offer="starter-plugin|vault|lead-magnet-machine|content-engine|dm-system|client-stack"` and a single JS config object mapping offer → URL, so future landing pages/checkouts are wired in one edit.
7. Mobile: homepage cards stack Inbound first; /offers tiers stack top-down; Allbound dark card first on /allbound.
8. 301s per Section 9. Update sitemap.xml and nav everywhere.
9. Global find/purge per Section 9 retired-assets list. Grep for `495`, `295`, `Foundation`, `Growth` before shipping.
10. Keep all existing imagery, analytics screenshots, testimonial walls — restyle only where a section moved from dark to light.
11. **Copywriting standard:** every rewritten line must be world-class direct-response copy — outcome-first, specific numbers over adjectives, the ICP's exact pain language (Section 10 ICP list), zero AI-sounding filler (no "unlock", "elevate", "seamless", "game-changer", "in today's digital landscape"). Headlines follow the existing pattern: dark headline + orange accent on the money words. When in doubt, shorter.
12. **Design skill:** whenever building or visually adjusting anything (the /offers page assembly, the Allbound dark card, any component that must be adapted), read and apply the frontend-design skill first so spacing, hierarchy, and polish match the existing pages instead of defaulting to generic component styling.

---
*End of Master Brand Resource File v3.0 · Malik Muzamil / Growlioo · July 2026*