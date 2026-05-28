# skill.md — TrackBox Codex Build Skill

## Purpose
Use this file as the main Codex skill/instruction layer for building the TrackBox website from GitHub.

Codex must treat TrackBox as a premium immersive sports-performance brand, not a normal ecommerce template.

## Repository Setup Rule
Before making changes, Codex must verify it is working in the correct GitHub repo and branch:

- Repository: jimmybernatek-spec/TrackBox-Items
- Branch: main

Codex must sync or pull the latest main branch before editing.

Codex should verify these files exist locally:

- AGENTS.md
- skill.md
- docs/trackbox-master-context.md
- docs/brand-guide.md
- docs/ui-system.md
- docs/motion-system.md
- docs/cinematic-asset-library.md
- docs/spline-scenes.md
- docs/homepage-3d-scroll-experience.md
- docs/active-theory-resn-reference.md
- docs/products-and-boxes.md
- docs/sponsors-section.md
- docs/pole-vault-miami-context.md

If these are missing locally, Codex is in the wrong workspace or outdated branch and must stop and sync before proceeding.

## Brand Identity
TrackBox is an athlete preparation ecosystem built around fuel, hydration, recovery, competition readiness, training systems, Session Packs, products, partners, and coaching integration.

Core message:
Prepared Athletes Perform Differently.

TrackBox should feel like:
- Premium sports-tech
- Dark athletic performance
- Immersive and cinematic
- Scientific and high-performance
- Interactive and motion-driven

TrackBox should not feel like:
- A generic ecommerce store
- A simple Shopify-style product site
- A startup SaaS template
- Basic Tailwind blocks
- Static stacked sections

## Primary References
Use these as inspiration for interaction quality and cinematic polish only:

- https://activetheory.net
- https://resn.co.nz
- https://www.apple.com/apple-vision-pro/
- https://www.whoop.com
- https://www.nike.com

Do not copy proprietary work. Match the level of immersion, polish, depth, and motion quality.

## Design System
Use:
- Matte black backgrounds
- Deep charcoal surfaces
- White typography
- Cool gray secondary text
- Neon blue accents
- Neon pink accents
- Subtle haze, glow, particles, and depth blur

Avoid:
- Flat gray card stacks
- White-box layouts
- Generic pricing tables
- Hard cuts between sections
- Plain image rectangles

## Motion System
Motion is part of the brand.

Use:
- Three.js
- GSAP ScrollTrigger
- Framer Motion
- Spline where useful

Motion should include:
- Scroll-controlled scenes
- Parallax depth
- Floating objects
- Camera movement
- Hover-responsive panels
- Cinematic transitions
- Atmospheric particles
- Text sequencing

Avoid:
- Cheap bounce effects
- Random motion
- Simple fade-ins only
- Abrupt transitions

## Homepage Requirement
The homepage must start with a full-screen immersive 3D TrackBox sequence.

Sequence:
1. Dark athletic environment loads.
2. Subtle particles and haze appear.
3. Camera moves toward TrackBox.
4. TrackBox becomes the dominant center object.
5. Box rotates subtly with cinematic lighting.
6. Box opens during scroll.
7. Products fly outward.
8. Products orbit around TrackBox.
9. Text overlays appear: Fuel. Hydrate. Recover. Compete.
10. Transition smoothly into normal homepage content.

The 3D intro should be pinned/fullscreen until the sequence completes.

## Page Sections
Build or improve these sections:

1. What Is TrackBox
2. Choose Your TrackBox
3. Session Packs
4. What's Inside
5. Athlete Preparation System
6. Performance Partners / Sponsors
7. Pole Vault Miami Integration
8. Team Sales
9. Community / Events
10. Final CTA

Every section should feel connected, cinematic, and visually cohesive.

## Session Packs
Session Packs must be presented as a system:

- PRE
- DURING
- POST
- RECOVERY
- COMPETE

This should feel tactical, scientific, and athlete-focused.

## Sponsors
Sponsors should be data-driven and editable.

Support fields:
- name
- category
- tier
- description
- whyItFits
- logoPath
- featuredImagePath
- productImagePath
- websiteUrl
- instagramUrl
- discountCode
- partnershipStatus
- featured

Never claim a company is an official sponsor unless TrackBox has confirmed it.

## Asset Usage
Use uploaded repository assets whenever available.

Look in:
- public/assets/trackbox/backgrounds
- public/assets/trackbox/particles
- public/assets/trackbox/mockups
- public/assets/trackbox/products
- public/assets/trackbox/packaging
- public/assets/trackbox/sponsors
- Trackbox/

Do not ignore uploaded box images or mockups.

Do not place assets in plain rectangles. Integrate them through layering, glow, parallax, and scene composition.

## Deployment
Prepare for Vercel deployment unless otherwise specified.

Codex should ensure:
- package.json exists if using React, Next, or Vite
- build command works
- assets use public paths
- no local-only paths are used
- site works when deployed
- mobile fallback exists for heavy 3D scenes

## Final Standard
The final site should feel like:
Nike x WHOOP x Apple Vision Pro x Active Theory x Resn.

The user should immediately believe TrackBox is a serious premium sports-performance company.