# DESIGN INTELLIGENCE — DAILY LEARNINGS

Auto-maintained by daily cron. Each morning: 5 premium/award-winning sites deep-analyzed.
Newest entries on top. When building ANY UI, consult the "DISTILLED PRINCIPLES" section first.

Reference sites seed list (rotate, never repeat within 14 days):
jeskojets.com · jitter.video · awwwards.com (SOTD) · godly.website · land-book.com ·
httpster.net · minimal.gallery · cofolios.com · refero.design · siteinspire.com

---

## DISTILLED PRINCIPLES (rolling synthesis — update each run)

> The agent rewrites this section each day: merge new learnings, drop noise, keep the
> highest-signal rules. This is the part read at build time. Keep it tight + actionable.

### Typography
- Build hierarchy from TWO registers, not five: one expressive display (heavy grotesque or high-contrast/transitional serif) + one quiet utility sans. Kill the ambiguous mid-tier.
- Use a large display-to-body ratio (~8-10x). If a size could be either heading or body, it is wrong — make it clearly "monument" or "caption."
- All-caps + wide letter-spacing on a serif reads as couture/luxury; reserve it for short section titles, never paragraphs.
- Let one giant type element BE the hero (the object), not a caption sitting above a stock photo.
- Pair a poetic/emotive headline with hard technical data in a contrasting register (e.g. soft lowercase manifesto + small mono spec caps).
- Tight tracking on big display weights; comfortable line-height + sentence case on body for warmth.

### Layout & Grid
- Asymmetric, editorial, image-led grids beat centered-blob layouts. Offset copy; one side image, other side a short label + single CTA.
- Lead with feeling: full-bleed hero image/video + aspirational copy first; defer dense functional UI (booking, specs, forms) into slide-in/reveal panels.
- Give tall portrait, high-res photography room to breathe — it should carry the page's color and energy.
- Minimal floating nav with anchor links; keep chrome sparse so content leads.
- Design the "minor" pages too (404, info, contact) — art-direct everything, not just the home hero.

### Color & Contrast
- Commit to a tiny palette: 2 colors done with conviction (one ground + one accent) beats a 6-swatch palette. Reserve the accent for action/emphasis only.
- NEVER ship pure #fff for a premium brand — warm it to ~#F4F2EE / off-white. Pure white is a cheapness tell.
- Keep UI chrome near-monochrome and let photography/video supply the color.
- Low saturation + calm neutrals read expensive; bright synthetic brand colors competing with product imagery read cheap.
- Pull accent tones from the photography rather than inventing a synthetic brand color.

### Motion & Interaction
- GSAP + scroll is the premium default: scroll-reactive kinetic type, scroll-triggered reveals, weighted page transitions.
- Easing should be slow and eased-out — luxury moves calmly; restraint comes from the locked palette, not from killing motion.
- Hover-reveal video previews (portfolio/work) and subtle microinteractions signal craft; a custom cursor/hover system is the portfolio's "voice."
- Gaussian-blur / depth / parallax "looking-through-glass" transitions for immersive brands; slide panels in, don't pop them.
- Motion IS proof of skill for portfolios and the brand's personality for products — make it intentional, never decorative jitter.

### Spacing & Rhythm
- Generous whitespace around loud type so a single accent color never collides with content.
- Large vertical spacing between sections creates a slow, expensive scroll cadence.
- Air around every element is the anti-cheap move; crowding + pure white + compressed images is what looks templated.
- Keep copy blocks short and offset within the rhythm — never long centered paragraphs.

### What makes it feel "expensive" / not AI-generated
- Off-white (not #fff) grounds + q=100 uncompressed, high-res photography; next-gen formats (.avif/.webp) so big visuals stay fast (performance = premium).
- A strictly locked 2-color or monochrome system applied with discipline.
- Bespoke "hand-built" details: live local-time meta, hover-video previews, art-directed 404s, literal blueprint/diagram art, inline SVG.
- Editorial-poster discipline applied to unexpected subjects (e.g. a burger shop treated like a couture poster).
- Two type registers + asymmetric editorial grid + slow weighted motion. Avoid: Inter, purple gradients, centered hero + three cards, pure-white crowding, compressed JPEGs.

---

## DAILY LOG

<!-- Newest entries appended here by cron. Format below. -->

### 2026-06-17
**1. Crav Burgers — cravburgers.shop** (Awwwards SOTD 2026-06-17, 7.25)
- Typography: Type is the entire UI — oversized, tightly-tracked display lettering set as the hero "object," not a label sitting above an image. Heavy/black weights for the headline, a clean grotesque for the small body/spec text. Big size jump (display vs body, roughly an 8-10x ratio) so there is no ambiguous mid-tier — only "monument" and "caption."
- Layout: Deliberately playful and asymmetric for an e-commerce/ordering flow; full-bleed motion stages instead of the standard product grid. Whitespace is generous so the loud type and single red accent never collide.
- Color: Strict 2-color system — warm cream #f5e3cd ground + a single hot red #f91814 accent. No third color, no gradient. The cream reads "appetite/craft," the red is reserved for action and emphasis only. Two colors done with conviction outperforms a 6-swatch palette.
- Motion: GSAP-driven, Next.js + inline SVG. Scroll-reactive kinetic type and smooth state transitions on the ordering steps; motion makes a transactional flow feel like a toy, which is the brand point. Restraint comes from the locked palette, not from quiet motion.
- Expensive factor: A junk-food product treated with editorial-poster discipline; the 2-color lock + monumental type signals art direction, not a Shopify template.
- Lesson to steal: Pick 2 colors and commit. Let one giant type element BE the hero rather than captioning a stock photo.

**2. Elicyon — elicyon.com** (Awwwards Honorable Mention, luxury interiors)
- Typography: All-caps spaced serif/transitional display for section titles (OUR SERVICES, THE STUDIO) — wide letter-spacing on uppercase reads as couture, not shouty. Sentence-case humanist body underneath for warmth. The caps/serif + lowercase/sans pairing is the entire hierarchy.
- Layout: Editorial, image-led grid. Tall portrait photography (1800x2409) at high quality (q=100) given room to breathe; copy blocks are short and offset, never centered-blob. Asymmetric two-column rhythm where one side is image, the other is restrained label + single CTA.
- Color: Near-monochrome — warm off-white #F4F2EE + true black #000000. The warm white (not pure #fff) is the luxury tell; it removes the clinical/cheap feel of pure white. Photography supplies all the color.
- Motion: Next.js + Sanity + Vercel. Scroll-triggered reveals, project-preview video on hover, subtle microinteractions and page transitions. Motion is slow and weighted — luxury moves calmly.
- Expensive factor: Pure-#fff avoidance (#F4F2EE), q=100 uncompressed imagery, and air around every element. Cheapness is usually crowding + pure white + compressed JPEGs; this is the inverse.
- Lesson to steal: Never ship pure #fff for a premium brand — warm it to ~#F4F2EE. Let high-res photography carry the color and keep the UI chrome monochrome.

**3. Explora Journeys — explorajourneys.com** (luxury cruise, Winkreative brand)
- Typography: Refined high-contrast serif for emotive headlines ("Ocean State of Mind") paired with a quiet sans for utility/booking UI. The brand is built "by feeling rather than function," so display type is expressive while functional type recedes.
- Layout: Immersive full-viewport imagery with a minimal floating top nav (logo center, sparse icons). Booking/utility chrome is intentionally understated so the photography and aspirational copy lead; dense functional content (reserve, manage, contact) is tucked into reveal panels, not bolted onto the hero.
- Color: Coastal restrained neutrals — sand/ivory grounds with deep ocean tones, accents pulled from photography rather than a synthetic brand color. Calm, low-saturation = expensive.
- Motion: Smooth Gaussian-blur/depth transitions and gentle parallax evoking "looking through glass"; nav and overlay panels slide rather than pop. Easing is slow and eased-out.
- Expensive factor: An "ocean state of mind" mood-led IA — emotion-first hero, utility hidden until needed — so a complex booking engine still feels like a quiet luxury brochure.
- Lesson to steal: Lead with feeling, hide the machinery. Put aspirational copy + full-bleed image first; defer dense functional UI into slide-in panels.

**4. Jesko Jets — jeskojets.com** (private-jet charter, agency: The First The Last)
- Typography: Confident lowercase grotesque for the manifesto hero ("we are movement / we are difference") — short declarative lines, big and quiet. Spec data (range 11,263 km, 480 knots) set in small mono-ish caps as a precise counterpoint to the soft headline. Two registers: poetic + technical.
- Layout: Manifesto hero with anchor-nav (About / Our Fleet / Advantages / Global), then data-dense fleet spec blocks paired with .webp jet renders and .avif blueprint diagrams. Generous vertical spacing between sections gives a slow, expensive scroll cadence.
- Color: Muted dark/neutral aviation palette; restrained, near-monochrome with photography and blueprint line-art doing the visual work. No bright brand color competing with the product imagery.
- Motion: Smooth scroll, sectioned reveals, form micro-states (Request sent / Thank you). Modern .avif/.webp assets keep heavy imagery fast — performance IS part of the premium feel.
- Expensive factor: Pairing a soft poetic manifesto with hard engineering specs and literal blueprint diagrams — it sells precision and emotion simultaneously. AVIF blueprints are a detail no template ships.
- Lesson to steal: Pair a poetic hero line with hard technical specs in a contrasting type register. Use next-gen image formats (.avif/.webp) so big visuals stay fast.

**5. Artiom Yakushev — art-yakushev.com** (Awwwards Site of the Month, Jan 2026)
- Typography: Big editorial display headline ("Creative Digital Designer / Working Worldwide") with strong size contrast against tiny meta labels (local time "18:32", "Yerevan"). Confident, sparse, lots of negative space around the type.
- Layout: Portfolio as gallery — work surfaced via large hover-revealed video previews rather than a static thumbnail grid. Hero / Work / Info / 404 each get a distinct designed layout; even the 404 is art-directed. Built on Webflow + GSAP.
- Color: Restrained near-monochrome canvas so the project imagery/video provides all the color and energy. The neutral shell makes the work pop and signals editorial taste.
- Motion: GSAP-led parallax, filters/effects, weighted page transitions, and a custom-feeling cursor/hover system on the gallery. Easing is smooth and intentional — motion is the portfolio's "voice," proving craft.
- Expensive factor: Live local-time meta, hover-video work previews, and an art-directed 404 — small bespoke touches that say "hand-built," not Webflow-template.
- Lesson to steal: For a portfolio, motion IS the proof of skill. Use a monochrome shell + hover-video previews and design the "minor" pages (404, info) too.
