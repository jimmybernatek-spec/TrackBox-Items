# TrackBox 3D Homepage Scroll Experience

## Goal
Build a premium interactive 3D homepage intro directly into the TrackBox website.

This should be the first major visual experience on the homepage before the normal website sections begin.

## Core Experience
As the user scrolls:

1. The scene begins in a dark athletic environment.
2. The camera moves toward the TrackBox from a distance.
3. The TrackBox becomes the central focus.
4. The camera zooms around and in toward the box.
5. The box rotates slightly with premium lighting.
6. The lid opens.
7. Items fly out of the box.
8. Products orbit around the TrackBox like an organized athlete preparation system.
9. Product categories appear as short text callouts.
10. The animation transitions into normal homepage content.

## Product Items To Animate
Use placeholder 3D items first, then replace them with real assets later.

Items may include:
- Chalk block
- Athletic tape
- Hydration packets
- Snack GoBags
- Recovery snacks
- Protein/recovery items
- Spike replacements
- Training shirt
- Wrist guard
- Meet-day consumables

## Messaging During Animation
Use short premium copy:

- Fuel.
- Hydrate.
- Recover.
- Compete.
- Prepared Athletes Perform Differently.

## Technical Direction
Preferred implementation:
- Three.js for the 3D scene
- GSAP ScrollTrigger for scroll-based animation
- React components if the site is built as a custom frontend
- Spline embed only if faster visual prototyping is needed

## Website Behavior
The 3D intro should:
- Be smooth
- Feel premium
- Work on desktop first
- Have a simplified mobile fallback
- Not block normal website usability
- Fade naturally into the rest of the homepage

## Design Direction
The scene should feel:
- Dark
- Cinematic
- Matte black
- High contrast
- Athletic
- Scientific
- Premium
- Minimal

## Transition Into Normal Website
After the orbit scene, transition into:
- Choose Your TrackBox
- Essentials / Performance + Recovery / Premium
- What is inside the box
- Session Packs
- Build Your TrackBox
- Team sales
- Pole Vault Miami integration

## Important Notes For Codex
Codex should treat this as a real homepage feature, not just a design concept.

Build a modular system so the 3D scroll experience can be edited later.

The item list, text callouts, model paths, camera positions, scroll sections, and animation timings should be easy to update.