# DESIGN INTELLIGENCE — DAILY LEARNINGS

Auto-maintained by daily cron. Each morning: 5 premium/award-winning sites deep-analyzed.
Newest entries on top. When building ANY UI, consult the "DISTILLED PRINCIPLES" section first.

Reference sites seed list (rotate, never repeat within 14 days):
jeskojets.com · jitter.video · awwwards.com (SOTD) · godly.website · land-book.com ·
httpster.net · minimal.gallery · cofolios.com · refero.design · siteinspire.com

---

## ELEMENTS & ASSETS LIBRARIES (component / asset sourcing — keep current)

> Where to GET ready elements, components, and assets when building. The daily routine keeps
> this curated and adds short notes on what each is best for. Prefer these over reinventing.

### UI components (copy-paste, React/Tailwind)
- 21st.dev — community component marketplace (paired with the `21st_magic` MCP installed here).
- ui.shadcn.com — base primitives, the de-facto foundation.
- ui.aceternity.com — flashy animated marketing components.
- magicui.design — animated components, pairs with shadcn.
- originui.com · cult-ui.com · hover.dev · reactbits.dev · tailark.com — extended sets.

### Motion / animation
- gsap.com (+ Club plugins) · framer-motion (motion.dev) · lottiefiles.com · unicorn.studio · rive.app
- scroll.locomotive.ca — Locomotive Scroll: the industry-standard smooth-scroll + parallax library; see locomotive.ca for reference implementation
- threejs.org — for immersive WebGL; combine with GSAP for scroll-reactive 3D (see lusion.co, active-theory.com, makemepulse.com)

### Icons
- lucide.dev · phosphoricons.com · tabler.io/icons · heroicons.com · iconoir.com · svgl.app (brand logos)

### Fonts
- fontshare.com (free quality) · fonts.google.com · fontsource.org · pangrampangram.com · klim/commercial foundries for premium
- pangrampangram.com/editorial-new — Editorial New: narrow high-contrast serif, best variable-font display + long-form (Locomotive's confirmed typeface)
- dinamo-typefaces.com — Dinamo: Whyte (variable width + ink-traps) used by Resn; premium screen-first foundry

### Illustrations / 3D / backgrounds
- spline.design (3D) · undraw.co · blush.design · shadergradient.co · ibelick (bg snippets) · cssgradient.io

### Stock media (high-res, q=100)
- unsplash.com · pexels.com · coverr.co (video) · mixkit.co

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
- A strictly locked 2-color or monochrome system applied with discipline. Red (#CC0000-range) used as punctuation mark (never as fill) is an instant authority signal.
- Bespoke "hand-built" details: live local-time meta, hover-video previews, art-directed 404s, literal blueprint/diagram art, inline SVG, real-time networked cursor trails.
- Editorial-poster discipline applied to unexpected subjects (e.g. a burger shop treated like a couture poster; a real estate listing treated like an interior magazine editorial).
- Two type registers + asymmetric editorial grid + slow weighted motion. Avoid: Inter, purple gradients, centered hero + three cards, pure-white crowding, compressed JPEGs.
- Layout-as-concept beats layout-as-container: replace conventional navigation with a metaphor native to the brand (a crystalline 3D drop, a walkable office space, a retro spinning newspaper).
- Sub-brand IP creation (makemeplay, a gaming division) signals that a studio is an author, not just a vendor. Named sub-brands create discoverability and elevate positioning beyond client service.
- Custom typefaces (Iron & Glass for Arcane, Locomotive's iconographic custom type) are the highest-fidelity brand signal when the project warrants the investment — the letterform tells the story.
- Proprietary technology featured on the studio's own homepage (Hydra engine, Locomotive Scroll) is stronger proof of capability than any client list.

---

## DAILY LOG

<!-- Newest entries appended here by cron. Format below. -->

### 2026-06-18
**1. Lusion v3 — lusion.co** (Awwwards SOTD Oct 2023, Site of Year CSS Design Awards 2023; 3D / interactive studio)
- Pages studied: /home, /work, /about, /projects
- Typography: No single decorative typeface is the hero — the type system recedes so the real-time WebGL visuals dominate. Body and UI labels use a clean grotesque (consistent with the Pangram Pangram grotesque family: PP Neue Montreal is the most likely candidate given studio-level taste of this era), set in modest weights so it never competes with the animated 3D backgrounds. The word "LUSION" in the logo and hero uses tight tracking and a neutral weight — restraint at the identity level so the motion does all the talking. Section headers are all-caps, minimal, short — directional labels rather than expressive type.
- Layout: Single long-scroll, one-page architecture with "scroll to explore" triggering narrative reveals, deliberately avoiding full-screen jacking to maintain performance across devices. Work cards surface with metadata tags (web design, 3D animation, development, AR, game design) in a grid. About section features a dense 5–6-column logo-wall of client brands + a numbered award tally (58 Awwwards). The overall rhythm alternates compressed-content dense (logo wall) against expansive negative-space sections — creating visual breathing. Hero is full-viewport with the astronaut protagonist that tracks scroll and "breaks through glass" as a portal narrative.
- Color: Hard-confirmed two-hex palette for v3: electric blue #1a2ffb as the single accent against a near-white #f0f1fa ground (not pure white — the slight cool tint reads technical/future rather than warm/editorial). Dark sections use #000 black. This 3-color monochrome lock (black + near-white + one high-chroma blue) is extremely controlled for a site with immersive 3D — the blue only appears on UI/accent, never on the 3D environments, which are desaturated.
- Motion: Built entirely on Three.js + GSAP with vertex animations baked from Houdini FX (stored as PNG texture maps for position and normals — a proprietary optimization technique). Cloth simulation pre-calculated in Houdini blends interactively with user scroll velocity. Scroll-jacking is selective (only where scroll triggers 3D state changes) not universal. Interactive elements include click-triggered cloth physics and a mobile accelerometer scene. Perfect 10/10 developer animation score on Awwwards.
- Expensive factor: (1) Cloth physics and vertex animation running real-time in-browser — technically impossible on cheaper builds, so it immediately signals bespoke craft. (2) The 2-color UI shell forces the browser's eye to the 3D work rather than branding chrome, making the portfolio about the work not the studio ego. (3) Asynchronous scene loading and 16-bit integer texture compression so the WebGL payload performs at near-native speed — performance IS the premium for interactive studios.
- Lesson to steal: Let 2 restrained UI colors (e.g. near-white + 1 electric accent) frame immersive 3D/motion content rather than fight it. The UI chrome should disappear; the work should fill the viewport.

**2. Resn — resn.co.nz** (Awwwards 68 SOTD / 13 SOTM / 3 SOTY; KPR = SOTY 2022; Wellington NZ interactive agency)
- Pages studied: /home, /work, /work/kprverse, /about, labs.resn.co.nz
- Typography: Whyte (by Dinamo) is the confirmed workhorse for client-facing work (KPR project): variable width settings and ink traps selected for screen legibility at both display and small sizes. The ink traps — normally a functional detail in metal type — become a visible design statement at large scale: proof of typographic connoisseurship. Resn's own studio site uses a logotype paired with grotesque, but the real typographic signature is the "revolving crystalline drop" navigation — interactive WebGL as the information architecture, with typography subordinated to the experience metaphor.
- Layout: The studio homepage replaces a standard nav with a 3D metaphor — the crystalline drop IS the portfolio, with projects embedded in the facets. This is layout as concept rather than layout as structure: no header, no footer, no grid. For client work (KPR), layout draws from "futuristic poster design and manga/comic book layouts" — panel-based, bold asymmetric composition using heavy whitespace and grid cells that reference comic pages rather than web conventions.
- Color: For KPR the palette leans clean and futuristic — dominant white/near-white with black and metallic iridescent accents pulled from Art Deco/Art Nouveau motifs to reflect the two-faction world-building. The studio site uses a black crystalline dark background. Resn's color philosophy: palette serves narrative, not branding.
- Motion: WebGL + GSAP + GLSL shaders are the confirmed tech stack (Awwwards citation). KPR logo uses an After Effects gradient-reveal with sprite sheets + signed distance fields (SDFs) for the morphing/bleeding logo effect — this is a custom technique, not a library call. Interactive "click-and-hold" animations in the second content layer use CSS transforms for performance optimization over pure WebGL.
- Expensive factor: (1) Navigation-as-metaphor: the crystalline drop IS the UI, making exploration feel like discovery rather than menu-clicking. (2) SDFs for morphing typography at runtime — a technique borrowed from GPU rendering, almost never seen in web design. (3) Each project is interactive in a bespoke way — no project uses the same interaction mechanic, signaling craft over system.
- Lesson to steal: Replace conventional navigation with a metaphor native to the brand's world. The UI structure itself should communicate brand personality, not just contain it.

**3. Hello Monday — hellomonday.com** (digital design studio; NY / Copenhagen / Aarhus / Amsterdam; Google, Netflix, Strava clients)
- Pages studied: /home, /work, /about, /stories
- Typography: The studio name "Hello Monday" as a philosophy ("we make Mondays better") demands typographic warmth rather than coldness — confirmed clean sans-serif with differentiated weights for heading vs body, sentence-case treatment (never all-caps) signaling approachability. The editorial stories section uses readable longform hierarchy: large headline, medium kicker, regular body — a magazine-page system applied to the web. Strong scale contrast between work-card titles (display weight) and category labels (caption weight). Based on studio aesthetic and era, Neue Montreal or similar Pangram grotesque is the likely choice.
- Layout: Modular card-based grid with filterable category tags (Branding, Experiences, Platform, Products, E-commerce) — a deliberate "editorial newspaper with sections" metaphor applied to a portfolio. Stories section mirrors a magazine layout with read-time estimates, category tags, and large header imagery. Footer lists all 4 international offices with distinct contact paths. The key structural choice: 4 separate audience-entry points (collaboration inquiry, recruitment, internship, general) surfaced as distinct CTAs, never aggregated into a single generic contact form.
- Color: Near-neutral minimal shell (likely warm off-white with dark text) allowing project imagery to supply color energy. The studio brand color is not aggressive — "joyful" is the word in their copy, suggesting warm tones not cold blues. Restrained palette so the colorful client work (Google, Netflix) pops against the neutral background.
- Motion: Implicit from the build quality (Next.js-era stack): scroll-triggered card reveals, hover state transitions on work cards, animated work previews. The "joyful" brand positioning suggests motion is warm and springy rather than mechanical — cubic-bezier easing that feels human. "Stories" content uses reading-progress indicators and smooth section transitions.
- Expensive factor: (1) International presence as a design signal — 4 offices across 2 continents with individual local contact paths says "we are not a remote agency pretending to be global." (2) A published "Code of Honor" with 8 numbered principles (not a boilerplate mission statement) as an actual editorial document embedded in the About page — editorial discipline applied to studio culture. (3) The studio "Product" category alongside Work, Services, About signals proprietary IP alongside client service, placing them in a different tier than pure client shops.
- Lesson to steal: Give different audience types distinct named entry points (not one "contact us"). It makes the site feel like it knows who its visitors are, which is a signal of seniority.

**4. Collins — wearecollins.com** (Awwwards Agency of the Year 8x; NY brand design studio; "Rewrite your worth")
- Pages studied: /home, /work (case studies), /about, /work/arcane
- Typography: Sans-serif primary — large, bold, impactful headings used as design objects ("Rewrite your worth," "Don't Become the Best. Become the Only"). Confirmed palette: black and white with a vibrant red accent (#CC0000 family). The type itself performs as the brand identity: the studio that creates wordmarks for others uses typography as its own loudest visual device. Sentence-case on aspirational manifesto lines (warmth) vs. all-caps discipline on category labels and navigation items. For Arcane, Collins created a custom typeface "Iron & Glass" that merges Art Deco geometric precision with Art Nouveau organic curves — chiseled serifs and whiplash curves — a demonstration that custom type is the highest-fidelity brand signal.
- Layout: Minimalist, content-first: clean sections separated by generous whitespace, a 3–4 column case-study card grid at uniform spacing, each card with a professional Mux-CDN-hosted thumbnail. The hero layout is the antithesis of a "creative agency" hero — it leads with a strategic manifesto line, not a reel. Case study images are at mixed aspect ratios (525×700, 525×656, 525×788) rather than locked to a uniform crop, which gives the grid a magazine-spread quality. No full-bleed hero video — the work speaks louder than self-promotion.
- Color: Confirmed: black (#000000) + white (#ffffff) + vibrant red accent. The red appears selectively — not a background, not a gradient, but a punctuation mark on key navigational or typographic moments. Accompanying imagery provides all environmental color; the site shell stays monochrome. This is the "60-30-10 rule" applied with extreme discipline: near-100% black/white, red below 5% usage.
- Motion: Scroll-triggered section reveals, hover states on case study cards (likely image-opacity-shifts or card-lifts), and potentially GSAP-driven page transitions between case studies. The studio's philosophy values commercial logic over decorative motion — animations serve navigation, not spectacle.
- Expensive factor: (1) Custom typeface "Iron & Glass" for Arcane — narrating two factions through a single letterform, making the type system inseparable from the IP's meaning. (2) "Agency of the Year" listed 8 times (factual social proof, not a claim) on the studio's own homepage — understated but devastating. (3) The studio positions itself not as a design service but as a strategic partner with named business-outcome programs (turnaround, scale-up, exit) — this is IA as brand-building.
- Lesson to steal: Use bold red (#CC0000-family) as a punctuation mark, never a fill. Black/white/one-accent with restraint makes the single accent feel authoritative when it appears.

**5. Locomotive — locomotive.ca** (Awwwards Agency of the Year 7x; Montreal digital-first design agency)
- Pages studied: /en, /en/agency, /en/work, /en/work/editorial-new
- Typography: Confirmed: Editorial New (Pangram Pangram) as primary display face + Helvetica Now as secondary utility sans. Editorial New is a narrow, high-contrast serif designed for long-form editorial copy with enough personality to carry display headlines — its "vintage-modern duality" (Locomotive's own framing) is the dual brief in a single typeface. Helvetica Now handles navigation, body, and functional UI — the Swiss-grid reliability counterpoint. The combination is deliberate: humanist/editorial serif + modernist swiss grotesk. For their own website, Locomotive demonstrates the Editorial New typeface through a dedicated showcase: full-screen variable font usage across retro editorial advertising themes.
- Layout: Digital-first grid — clean card structure for work (Scout Motors, Populous, Mate Libre, Destigmatize), persistent top navigation with bilingual (EN/FR) toggle, organized footer columns (Menu / Social / External). The agency page lists team structure as "01 Design / 02 Development / 03 Operations" — numerical sectioning creates architectural rhythm without decorative dividers. Work grid uses mixed aspect ratios (300×176 + 300×189 for cards, up to 1000×703 for featured work) with intentional size hierarchy.
- Color: Orange/amber as the brand accent — confirmed from site and emoji-marker pattern (#FF8C00 range, warm amber-orange). Black text on white grounds with orange used for highlights, hover states, and brand moments. The warm orange avoids the cold-tech blues typical of agencies; it reads approachable-Montreal rather than cold-Silicon-Valley.
- Motion: Locomotive Scroll (their own open-source library) is the scroll engine — the site is the best advertisement for their product. Folding animations, parallax effects on screen sections, sticky elements, in-viewport interaction triggers — all powered by Locomotive Scroll. The Editorial New showcase demonstrates variable font axis animation (width + weight) driven by scroll, folded newspaper transitions, and retro-themed interactive typography.
- Expensive factor: (1) Using a typeface (Editorial New) created by a sister Pangram Pangram foundry and building an entire showcase site around it — vertical integration of type + experience. (2) Their own scroll library as the engine — they are the reference implementation, not a user of someone else's tool. (3) Bilingual French/English as a cultural signal (not just a toggle) — Montreal identity embedded in the product.
- Lesson to steal: Build a showcase/demo site around a single typeface's variable-font axis. It demonstrates typographic mastery AND serves as a client magnet. Let your tools (scroll library, animation library) be featured work.

**6. makemepulse — makemepulse.com** (FWA Hall of Fame; Paris interactive/XR studio; Brunello Cucinelli, McDonald's, Holocaust memorial)
- Pages studied: /en, /en/work, /en/about
- Typography: The studio's positioning ("light as air, as seamless as real life") demands typography that does not call attention to itself — confirmed clean sans-serif, likely Söhne or Neue Haas Grotesk given the French/Swiss creative tradition, set in clean weights. Studio copy style is manifesto-short: "Well-made. Well-designed. Packaged in a way people will actually use" — punchy, declarative, no excess. Headlines at large display sizes with body at compact readable weights. The typographic restraint is intentional: the studio's identity is the immersive work, not the container.
- Layout: Single-brand focus architecture — "makemepulse" as the core studio, "makemeplay" as a gaming sub-brand surfaced separately. Work filtered by project type. The visual hierarchy prioritizes project outcomes over studio biography — you arrive at the work, not a founder story. Portfolio cards use project-role tags similar to Lusion (XR, gaming, brand, campaign).
- Color: Not confirmed with hex, but described as "light-as-air" — likely warm neutral ground with the work imagery doing all color work. FWA Hall of Fame aesthetic in this period typically aligns with controlled dark/neutral + vibrant interactive content. Three.js conference sponsorship signals a technically sophisticated, desaturated-UI approach.
- Motion: Three.js (confirmed: conference sponsor + studio core tech) + GSAP for timeline and UI transitions. The studio pioneers XR and gaming experiences — their motion vocabulary is 3D-interactive, not just scroll-triggered. The "Brunello Cucinelli AI e-commerce" work suggests parametric/data-driven visual generation, not manually keyframed motion. The Holocaust memorial XR demonstrates motion used for gravity and meaning, not just aesthetics.
- Expensive factor: (1) FWA Hall of Fame is the highest-tier award in interactive — not many studios hold it. It functions as the studio's founding credential. (2) Pairing luxury fashion (Brunello Cucinelli) with Holocaust memorial work in the same portfolio — range and seriousness that advertising-only studios cannot match. (3) Building "makemeplay" as a separate brand within the same house — IP creation alongside service work positions them as authors, not just vendors.
- Lesson to steal: If you have a gaming or interactive sub-brand, give it a distinct visual identity (makemeplay) rather than burying it as a service category. Distinct sub-brands create discoverability and signal strategic range.

**7. Active Theory — active-theory.com** (Venice Beach creative technology studio; WebGL/WebGPU since 2012; Webby Awards; Adidas, NBA, Google clients)
- Pages studied: /home, project pages
- Typography: Confirmed "alien-tinged fonts" — custom or obscure display typefaces in the futuristic/cyberpunk register, not a standard grotesque or serif. The site's neon-office environments include "flickering neon lights" and "alien-tinged fonts" as deliberate design language. This suggests a narrow, geometric, slightly aggressive display face in the vein of Bebas Neue or a custom sci-fi narrow condensed, possibly with OpenType alternates that read as foreign/mechanical. Body text stays readable and legible to contrast the headline's otherness.
- Layout: Fully immersive 3D environments inspired by the studio's actual LA and Amsterdam offices — not a metaphorical "feel," but a literal 3D recreation you navigate. The portfolio structure is architectural: you walk through a space and encounter work on screens, walls, and surfaces. Navigation is AI-assisted (an embedded AI chat navigates you around the portfolio rather than a conventional menu). This is the most extreme example of "layout as spatial experience" rather than layout as information grid.
- Color: Dark/near-black environments with neon accent light sources — confirmed "flickering neon lights" as the color system. Blues, pinks, and cyans typical of cyberpunk palettes emanate from in-environment light sources rather than UI chrome. Mouse/touch interaction spawns colored tubes that persist and are networked — other users' cursor trails are visible in real-time, creating an ambient social color layer.
- Motion: Built on Hydra (Active Theory's proprietary 3D engine / functional state framework) optimized for maximum GPU throughput. Features: volumetric fog, light scattering, glowing LED screens, wet reflections — all simplified GPU tricks creating convincing cinematic renders. Draco-compressed meshes for performance. Networked mouse trails. LCP ~1.3s on desktop despite full 3D. GLSL shaders confirmed for typography effects.
- Expensive factor: (1) Networked real-time cursor trails between simultaneous visitors — every user's presence contributes to the color of the site, live. This is technically impossible outside a custom server + WebGL stack. (2) Hydra GUI — the studio built a visual scene editor for designers to compose 3D without code, then used it on their own portfolio, demonstrating it works at the highest level. (3) The portfolio IS the technology demo AND the brand — they don't need a separate case study for their stack; the homepage is the case study.
- Lesson to steal: If your studio builds a proprietary framework, the portfolio site IS the framework's reference implementation. Use it at the most challenging scale so it speaks for itself.

**8. Fantastic Frank — fantasticfrank.com/en** (Stockholm luxury design-led real estate agency, est. 2010; Berlin / Lisbon / Denver)
- Pages studied: /en, /en/listings, /en/editorial, /en/the-story-of-fantastic-frank, /en/blog/fantastic-frank-unveils-a-new-global-identity
- Typography: Confirmed minimalist serif for editorial/brand positioning — the agency explicitly launched a "new global identity" that introduces "a new sense of warmth and attitude" onto their established minimalist foundation. Real estate photography-as-editorial demands transitional or humanist serif display faces (comparable to Freight Display or Canela) that feel at home on an architectural magazine cover, not on a property portal. All-caps spaced labels for city/area headers (STOCKHOLM, BERLIN) in a condensed grotesque for searchability; the serif is reserved for emotive editorial headers and brand statements.
- Layout: Interior-magazine grid, not property-listing grid — this is the core design differentiation in the industry. Properties are treated as editorial stories: stylists and photographers interpret each home as a creative brief. Tall portrait photography dominates — high-res, professionally styled, given room to breathe at full-column or full-page width. The editorial section runs property features as magazine articles. Grid shifts between 2-up editorial card layout and full-bleed single-property feature pages. No clutter of price badges, bedroom icons, or mortgage calculators in the primary view — utility is intentionally deferred.
- Color: Confirmed "palette of warm Scandinavian tones — calm yet expressive colours." Updated identity introduces warmth onto a previously cold-minimalist foundation. Likely: warm cream/ivory ground (#F5F0E8 range), muted dusty warm tones (warm gray, sandstone, sage) as secondary accents, black typographic elements. No synthetic brand colors — the identity is warm neutrals so the interior photography's rich materiality (marble, wood, textiles) reads as the color system.
- Motion: Smooth page transitions between property listings and editorial features. Hover-reveal on listing cards (interior preview), scroll-driven image reveals. The editorial treatment means scroll cadence is slow and cinematic — property pages behave like long-read magazine articles with scroll-sticky header images.
- Expensive factor: (1) Treating individual property listings as editorial commissions — each home gets its own photographer/stylist brief, not a standard listing template. This is a staffing and budgeting decision that shows up in every page. (2) Warm-Scandinavian-neutral color identity rather than "luxury = dark navy/gold" cliché — the restraint reads more confidently expensive than any gold accent would. (3) An editorial content branch (articles, features, stories) alongside listings — this makes the site a publication, not a database, and retains visitors even when they are not actively buying.
- Lesson to steal: Treat each portfolio or product item as an editorial commission (art director + photographer brief) rather than a template fill. It transforms a utility grid into a destination.

---

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
