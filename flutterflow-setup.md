# Using this package with FlutterFlow

## Before you start
Keep any existing KIXORA Lite project as a backup. This design package is for the new KIXORA project.

## Recommended workflow
1. Open `assets/kixora_full_ui_design_reference.png` to use as the overall visual reference.
2. In FlutterFlow, create or open your blank **KIXORA** project.
3. Use FlutterFlow Designer if it is available in your account. Generate one or a few screens at a time; a large multi-screen prompt may not create all pages consistently.
4. Use `design-system.md` to set colours, typography, corner radii, and spacing.
5. Use `screen-specifications.md` to build pages and shared components in FlutterFlow.
6. Create the shared bottom navigation once, then reuse it across the five main tabs.
7. Replace placeholder avatars, posts, and media with your own licensed assets.
8. Connect real backend features only after the layouts and navigation are stable.

## If Designer asks for a prompt, start with this
Design a polished mobile-first social networking app called KIXORA with the tagline “Connect. Share. Belong.” Use a dark navy background (#050A18), raised navy cards (#0B1530 and #102044), electric cyan (#00E5FF), blue (#168BFF), purple (#8B5CF6), bright white text, and muted blue-grey secondary text. Use rounded cards, restrained gradient accents, modern sans-serif typography, and consistent spacing. Match the supplied KIXORA design reference: deep navy/black backgrounds, bright cyan and electric-blue outlines, a cyan-to-purple KIXORA mark, compact rounded panels, luminous blue accents, and consistent mobile bottom navigation. Create an editable Home Feed screen with a KIXORA header, search and notification icons, stories row, post composer, photo/video feed cards with Like/Comment/Share actions, and a bottom navigation bar for Home, Clips, Explore, Messages, and Profile. Keep the design accessible, uncluttered, premium, and consistent with the KIXORA visual reference. Brand must say KIXORA, never KIXORA Lite.

## What this ZIP does not do
- It does not import all screens into FlutterFlow automatically.
- It does not create a production backend or real authentication.
- It does not make chat, video hosting, recommendations, or notifications functional by itself.

Those parts need implementation and testing in FlutterFlow plus a configured backend.
