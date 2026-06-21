always use these two thing:
1.use agent.md , gemini.md, claude.md for making the project.
2.use design.md to make the design of the website and take inspiration from that.

---

# InAmigos NGO Awareness Webpage

## Architecture & Layout (Astro)
- **Framework**: Astro 6.x
- **Layout File**: [Layout.astro](file:///c:/Users/ADITHYA/Desktop/Projects/InAmigos/src/layouts/Layout.astro) - Setup with Google Fonts (Sofia Sans & Inter), global design system variables matching Mastercard aesthetic, and optimized SEO headers.
- **Pages**: [index.astro](file:///c:/Users/ADITHYA/Desktop/Projects/InAmigos/src/pages/index.astro) (entry page).

## Core UI Components
1. **[Navbar.astro](file:///c:/Users/ADITHYA/Desktop/Projects/InAmigos/src/components/Navbar.astro)**: Floating, pill-shaped navigation container (`border-radius: 999px`) offset 24px from top. Collapses into a responsive hamburger overlay on mobile viewports.
2. **[Hero.astro](file:///c:/Users/ADITHYA/Desktop/Projects/InAmigos/src/components/Hero.astro)**: Features a large-scale display heading, dual-button group, and a Mastercard-inspired stadium-shaped media banner (`border-radius: 40px`).
3. **[About.astro](file:///c:/Users/ADITHYA/Desktop/Projects/InAmigos/src/components/About.astro)**: Introduces the NGO's history and legal registrations (80G, 12A, NITI Aayog, ISO 9001:2015) using an asymmetrical 2-up block and a ghost watermark background.
4. **[Projects.astro](file:///c:/Users/ADITHYA/Desktop/Projects/InAmigos/src/components/Projects.astro)**: Constellation of 6 key initiatives (BachpanSala, Udaan, Jeev, Seva, Prakriti, Vikas). Renders images as perfect 50% radius circles with attached white satellite circular CTAs, interconnected by green SVG dashed orbital arcs.
5. **[Stats.astro](file:///c:/Users/ADITHYA/Desktop/Projects/InAmigos/src/components/Stats.astro)**: Numeric callouts showcasing key on-ground success metrics in India.
6. **[CTA.astro](file:///c:/Users/ADITHYA/Desktop/Projects/InAmigos/src/components/CTA.astro)**: Contrasting dual-card action prompts (White background for donating, Ink Black background for volunteering).
7. **[Footer.astro](file:///c:/Users/ADITHYA/Desktop/Projects/InAmigos/src/components/Footer.astro)**: Tall near-black (`#141413`) directory structure including contact links, social icons, and country dropdown pill.