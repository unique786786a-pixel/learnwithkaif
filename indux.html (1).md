# BrandNest Website: Master Build Prompt

> Attach with this prompt: (1) the BrandNest logo image, (2) a screenshot of the Dribbble reference "Carlos Personal Portfolio Website".

---

## ROLE

You are a senior product designer and front-end engineer who builds award-level portfolio websites for creative studios. Build a complete, production-ready, single-page portfolio website for **BrandNest**, a boutique digital growth studio run by **Kaif**.

## REFERENCE

Use the attached Dribbble shot (Carlos Personal Portfolio Website) as the **layout and feel reference**, not something to copy. Borrow:

- The confident, personality-led hero with oversized type
- The generous whitespace and clear editorial grid
- The way work is presented as large, visual, clickable showcases
- The clean, uncluttered navigation

Do **not** copy its colors, text, imagery or exact layout. The final result must be unmistakably BrandNest: a **premium black and gold studio** that feels bespoke, not templated.

## BRAND

- **Name:** BrandNest
- **Descriptor:** Digital Growth Studio
- **Logo tagline:** "Where brands grow."
- **Founder:** Kaif
- **Positioning:** BrandNest helps local businesses, startups, creators and growing brands improve their branding, social media, content, websites and customer enquiries.
- **Personality:** modern, creative, professional, friendly, young, strategic, results-oriented, approachable.
- **Core feeling to create:** "This person understands branding, content, websites and digital growth as one complete system." Creative thinking + marketing strategy + professional execution.

### Logo usage (use the attached logo)

- The mark is a gold "B" containing an "N" with an upward arrow (growth). The wordmark is **BRAND** in white and **NEST** in a gold gradient, wide-tracked sans-serif caps, with a small spaced-out tagline beneath.
- Use the supplied logo file for the navbar, footer and favicon. If a clean transparent version is not available, recreate the wordmark in live text (white "BRAND" + gold-gradient "NEST").
- Make a simplified icon-only version of the "B" mark for the favicon, the mobile navbar and the loader.

## DESIGN SYSTEM

**Direction:** premium dark editorial with selective light sections for contrast. Clean, minimal, bold type, large whitespace, subtle gold gradients, restrained glassmorphism on the navbar and floating UI only.

**Colors (take the exact gold from the attached logo):**

| Token | Value |
|---|---|
| Background | `#0B0B0D` (near-black) |
| Surface | `#141417` / `#1B1B1F` |
| Text | `#F5F5F0` |
| Muted text | `#A1A1AA` |
| Gold (primary accent) | sample from logo, approx. `#F2B63A` |
| Gold gradient | light `#FFD875` → mid `#F2B63A` → deep `#C98A1E` |
| Light section bg | warm off-white `#F5F3EC`, with near-black text |

- Gold is the **only** accent. Use it for primary CTAs, key numbers, underlines, hover states, the process line and small decorative details. Never flood a section with gold.
- Alternate dark and light sections so the page has rhythm (for example Hero dark, Problem light, Services dark, Work dark, Process light, Final CTA dark).

**Typography:** Manrope (or Inter) from Google Fonts.
- Hero H1: oversized, fluid (`clamp(3rem, 8vw, 7.5rem)`), weight 700–800, tight line-height and tracking.
- Section labels: small, uppercase, wide letter-spacing, in gold.
- Body: 16–18px, line-height 1.6, high readability.

**Avoid:** generic agency templates, neon, heavy gradients, too many rounded cards, stock photos, over-animation, jargon, slogans like "We are the best agency".

## VISUALS (important, no stock photos)

Build all visuals in code/SVG/CSS so nothing looks cheap or broken:
- **Hero visual:** a layered, softly floating collage of an Instagram post mockup, a reel thumbnail (9:16), a mini website screen, a WhatsApp chat bubble, a small analytics card and brand elements (color swatches, type specimen), all in the black and gold palette. Subtle float animation, with a slight parallax on mouse move (desktop only).
- **Portfolio thumbnails:** generate stylish placeholder compositions per project (gradient + typography + mockup shapes), using each project's own mini-palette. Each must look like a real design, not a gray box.
- Make it easy to swap any placeholder for a real image later (`image` field in the content file).

## SITE STRUCTURE (single page with smooth-scroll anchors, plus case-study pages/modals)

1. **Navbar**: sticky; logo left; links Work, Services, Process, About, Contact; gold button "Get Free Audit". It turns translucent and blurred on scroll. Mobile: clean hamburger with a full-screen menu. Thin gold scroll-progress bar.
2. **Hero**
   - Label: `BRANDNEST: DIGITAL GROWTH STUDIO`
   - H1: **Your Business Deserves a Better Digital Presence.**
   - Sub: *We help businesses build stronger brands, create better content, and turn social media into a growth channel.*
   - Buttons: **Get a Free Digital Growth Audit →** (gold, primary) and **See Our Work** (outline)
   - Credibility line: Branding • Content • Websites • Social Media • Digital Growth
   - Microcopy: *We don't just make your business look good online. We build a digital presence designed to get attention, build trust and generate enquiries.*
   - Right side: the floating collage described above.
3. **Marquee strip**: BRANDING · SOCIAL MEDIA · REELS · WEBSITES · CREATIVES · WHATSAPP MARKETING · DIGITAL GROWTH. Slow, seamless loop; pauses on hover.
4. **Problem**: "Good businesses often look invisible online." Intro paragraph: a business can have great products and service yet still struggle to attract customers if its online presence looks inconsistent, outdated or inactive. Three numbered cards:
   - 01 Inconsistent Branding: Your Instagram, website, logo and promotional materials don't feel like the same brand.
   - 02 Content That Doesn't Convert: Posting regularly isn't enough. Your content needs to capture attention and communicate value.
   - 03 Missed Digital Opportunities: Potential customers may search for your business online and leave because they can't quickly find the information they need.
   Close with a bold line: **That's where BrandNest comes in.**
5. **Services**: "Everything your brand needs to grow online." Premium cards (hover reveals the "Includes" list):
   - **Branding**: logo direction, brand colors, typography, visual identity, brand guidelines → *Build My Brand →*
   - **Social Media Content**: Instagram posts, carousels, stories, content planning, captions, strategy → *Improve My Content →*
   - **Reels**: concepts, scripts, editing, hooks, captions, trend adaptation → *Create My Reels →*
   - **Promotional Creatives**: sale, product, festival, launch and ad creatives
   - **Websites**: landing pages, business websites, portfolio websites, mobile optimization, CTA optimization
   - **WhatsApp Marketing**: Business setup, catalog optimization, promotional messages, customer flows, CTA integration
   - **Digital Business Profiles**: Google Business Profile optimization, business information, digital profiles, contact optimization, local presence

   Write each short blurb in plain business language (e.g. "Turn your online presence into a consistent source of enquiries.").
6. **Featured Work**: "Work that makes brands look better." Category filters: All / Branding / Social Media / Reels / Websites / Campaigns. Large editorial grid (mixed sizes), hover zoom with a "View project" label. Projects (all **clearly badged "Concept Project"**):
   - Urban Brew Café (Cafe: Branding + Instagram + Reels): "Created a modern visual identity and social content system designed to make the café more discoverable and memorable."
   - FitCore Studio (Fitness: Social Media + Reels + Promotional Creatives)
   - Aurelia Beauty (Beauty: Brand Identity + Instagram + Promotional Campaign)
   - HomeCraft Interiors (Interior Design: Website + Branding + Social Media)

   Each card: name, industry, services, one-line goal.
7. **Case study** (modal or `/work/[slug]` page): Client/Concept, Industry, Challenge, Strategy, Creative Direction, Execution (bulleted deliverables), Outcome. Outcome text when no real data exists: **"Designed to improve brand consistency, visibility and customer trust."** Never show invented metrics. Include next/previous project navigation.
8. **Before & After**: "A better digital presence changes perception." Draggable comparison slider (touch + keyboard accessible). BEFORE: inconsistent graphics, weak profile presentation, poor visual hierarchy, generic promotional content. AFTER: consistent branding, professional content, stronger visual identity, clearer calls to action. Use generated mockups, labeled "Concept example".
9. **Industries**: "Built for businesses that want to grow." Eight cards with refined line icons (not emoji): Cafes & Restaurants, Salons & Beauty, Gyms & Fitness, Real Estate, Retail & Fashion, Clinics & Professionals, Coaches & Educators, Startups & Personal Brands. Statement: **If your customers are online, your business should be too.**
10. **Process**: "Simple process. Serious execution." Four steps with a connecting line that draws itself on scroll: 01 Discover (understand business, customers, competitors, goals), 02 Strategy (opportunities + practical growth plan), 03 Create (content, campaigns, website, digital assets), 04 Grow (refine from performance, feedback and goals).
11. **Why BrandNest**: "Why businesses choose BrandNest." Five points: Strategy + Creativity; Built for Your Business (no copy-paste templates); Simple Communication (no jargon); One Creative Partner; Growth-Focused. Make a prominent animated funnel: **Attention → Trust → Enquiries → Customers**.
12. **Results**: flexible stats band using placeholders (`+XX Projects Completed`, `XX+ Creative Assets`, `XX Businesses Supported`, `XX% Campaign Improvement`). Count-up animation only when real numbers are set. Content-file comment: "Replace these placeholders only with verified numbers." Hide the section in production while values are placeholders.
13. **Testimonials**: carousel component, but with no real testimonials yet, render the fallback: **"Currently building our client success stories."** + CTA **"Be one of our first featured success stories →"**. Placeholder testimonials must be marked internally and be easy to toggle on.
14. **Packages**: three cards, **Starter** (profile optimization, basic branding direction, monthly content, promotional creatives → *Start Growing →*), **Growth** (highlighted; content strategy, social content, reels, promotional creatives, WhatsApp marketing, monthly strategy → *Choose Growth →*), **Custom** (branding, website, social, content, reels, digital marketing, custom strategy → *Let's Build Your Brand →*). Price on every card: **Custom Quote**. No invented prices.
15. **Free Audit section** (strongest conversion block): "Want to know what's holding your digital presence back?" Text: *We'll take a quick look at your online presence and share practical opportunities to improve your branding, content and customer journey.* Form: Name, Business Name, Business Type, Instagram / Website, WhatsApp Number, What do you need help with? Button **Request My Free Audit**. Validate inline. Success message: **Thanks! We'll review your digital presence and get back to you.** Submit to a configurable endpoint (Formspree/Web3Forms/Next.js route) and, as a fallback, open WhatsApp with the form details pre-filled.
16. **About (Kaif)**: short, honest, personal block with a placeholder portrait slot (`[Kaif photo]`) and 2–3 lines on his approach. Do not invent biography facts; use editable placeholder copy.
17. **FAQ**: accessible accordion with six Q&As: What type of businesses do you work with? / Do you only manage Instagram? / Do you offer custom packages? / Can you work with a small business? / Do you provide websites? / How do we get started? (Answers: local businesses, startups, service businesses, personal brands and growing companies; no, branding, content, reels, websites, WhatsApp marketing and other touchpoints too; yes, custom packages; absolutely, designed to help growing businesses without unnecessary complexity; yes, modern mobile-friendly websites and landing pages; start with a free digital growth audit.)
18. **Final CTA**: full-width dramatic section. H2 **Let's make your brand impossible to ignore.** Sub: *Your business already has something valuable. Let's make sure the internet knows about it.* Buttons **Get a Free Digital Growth Audit →** and **Chat on WhatsApp**. Small line: Branding • Content • Websites • Digital Growth.
19. **Footer**: logo, "Digital Growth Studio", *"Helping businesses build better brands and stronger digital presence."*, nav (Work, Services, Process, About, Contact), services list (Branding, Social Media, Reels, Websites, WhatsApp Marketing), contact (Kaif, BrandNest: Digital Growth Studio) with **placeholder** Email / WhatsApp / Instagram / LinkedIn slots. © 2026 BrandNest. All rights reserved.
20. **Floating WhatsApp button**: bottom-right pill "Chat with Kaif" + "Let's discuss your business." Appears after a short scroll, collapses to an icon on mobile, never overlaps the form. Opens `https://wa.me/{WHATSAPP_NUMBER}?text=` + URL-encoded: *"Hi Kaif, I found BrandNest and I'd like to discuss improving my business's digital presence."*

## CONVERSION FLOW

Attention (hero) → Problem → Solution (services) → Proof (work) → Process → Trust (why us) → Offer (free audit) → Action (WhatsApp). Repeat the audit CTA naturally 4–5 times across the page without feeling pushy. Primary action: **Free Digital Growth Audit**. Secondary: **Chat with Kaif on WhatsApp**.

## MOTION

Premium and restrained. Hero text fades and slides up in sequence; hero collage animates into position; sections reveal on scroll (small upward move + fade, once only); portfolio images zoom slightly on hover; buttons scale about 1.03 with a gold transition; the process line draws on scroll. Use CSS/IntersectionObserver or a light library (Framer Motion is fine). Respect `prefers-reduced-motion`. Do not over-animate.

## RESPONSIVE

Design mobile intentionally, not as a squeezed desktop: the hero headline stays large and punchy; the collage simplifies to 2–3 key elements; the portfolio becomes a clean vertical stack; the services become swipeable or stacked cards; tap targets are at least 48px; the WhatsApp button and sticky CTA are thumb-friendly. Test at 360, 390, 768, 1024, 1280 and 1440 px.

## HONESTY RULES (non-negotiable)

Never fabricate clients, reviews, revenue, follower counts, campaign results, awards, partnerships or certifications. Where real data is missing, use clearly labeled **Concept Project**, **Sample Work**, **Coming Soon** or **Replace with real client result**. Do not invent contact details; use obvious placeholders. Trust comes from honest positioning.

## VOICE

Confident, not arrogant. Professional, not corporate. Friendly, not childish. Simple business language, no jargon. Say "We help businesses look better online and turn attention into enquiries", never "leading agency" or "revolutionary solutions".

## SEO, PERFORMANCE, ACCESSIBILITY

- Title: **BrandNest: Digital Marketing & Growth Studio**
- Meta description: *BrandNest helps businesses build stronger brands, better social media content, websites and digital growth strategies. Get a free digital growth audit.*
- Primary keyword: digital marketing freelancer. Secondary: digital marketing agency, social media marketing, branding services, Instagram marketing, website design, digital marketing for small businesses, digital marketing freelancer India, social media marketing for local businesses. Work these in naturally.
- Semantic HTML (one H1, logical H2/H3), Open Graph + Twitter cards, favicon from the "B" mark, JSON-LD (`ProfessionalService`), sitemap, clean URLs.
- Lazy-load below-the-fold media, use WebP/AVIF and responsive images, minimal JS, preload the font. Target Lighthouse 90+ for performance and 95+ for accessibility and SEO.
- WCAG AA contrast (check gold on black and gold on off-white), visible focus states, keyboard-operable menu, accordion and slider, alt text, labels on all form fields.

## TECH STACK

Next.js (App Router) + TypeScript + Tailwind CSS, with Framer Motion for animation. Reusable components: `Navbar, Hero, TrustMarquee, ProblemSection, Services, Portfolio, CaseStudy, BeforeAfter, Industries, Process, WhyBrandNest, Results, Testimonials, Packages, AuditForm, About, FAQ, FinalCTA, Footer, WhatsAppButton`.

**Easy editing:** keep ALL content in typed files under `/content` (`site.ts`, `services.ts`, `projects.ts`, `testimonials.ts`, `stats.ts`, `packages.ts`, `faq.ts`) and a single `config.ts` for WhatsApp number, email, social links and form endpoint. Kaif must be able to change projects, services, testimonials, stats, pricing, contact info and social links without touching components. Include a short README explaining how to edit content, set the WhatsApp number and deploy to Vercel.

## DELIVERABLES

1. The full working codebase with the structure above
2. Design tokens (colors, type scale, spacing) in `tailwind.config` / CSS variables
3. All sections above, fully responsive, with realistic placeholder visuals
4. README with setup, content editing and deployment steps
5. A short list at the end of anything Kaif must supply: logo file, WhatsApp number, email, social links, real projects, testimonials, verified stats, his photo

Build the whole thing in one pass, then self-review against: honesty rules, mobile layout, contrast, and whether the page feels like a premium boutique studio rather than a template.
