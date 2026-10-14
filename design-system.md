# KIXORA Design System

## Brand
- Name: KIXORA (never “KIXORA Lite”)
- Tagline: Connect. Share. Belong.
- Credit: Designed by Kitsamba Joshua
- Personality: premium, futuristic, welcoming, creator-focused, African-global.

## Colour tokens
- Background: `#050A18`
- Surface: `#0B1530`
- Raised surface: `#102044`
- Primary cyan: `#00E5FF`
- Electric blue: `#168BFF`
- Purple: `#8B5CF6`
- Main text: `#F5F8FF`
- Muted text: `#9BAAC8`
- Border: `#20345E`
- Success: `#34D399`
- Error: `#FB7185`

## Typography
Use Inter, Manrope, or the closest available FlutterFlow sans-serif font.
- Screen title: 24–30 px, semibold/bold
- Section heading: 16–20 px, semibold
- Body: 14–16 px
- Metadata: 11–13 px
Keep contrast high and avoid long text blocks on mobile.

## Shape and spacing
- Main card radius: 16–22 px
- Buttons: 14–18 px radius
- Avatar: circular, with a thin cyan/purple gradient ring for stories
- Base spacing scale: 4, 8, 12, 16, 20, 24, 32 px
- Page side padding: 16 px on mobile; 24–32 px on wider screens
- Use subtle borders and restrained glow; don't put a glow around every component.

## Core components
1. Primary gradient button: cyan → blue → purple.
2. Secondary button: transparent navy with cyan border.
3. Story avatar: circular image, gradient ring, small label.
4. Post card: author row, body, media, engagement counts, actions.
5. Bottom navigation: Home, Clips, Explore, Messages, Profile.
6. Search field: raised navy surface, search icon, muted placeholder.
7. Chips: rounded capsule with thin border; active chip uses cyan fill or gradient.
8. List row: icon/avatar, title, supporting text, trailing action/chevron.
9. Empty state: simple icon, clear headline, one helpful action.

## Accessibility and responsive behavior
- Maintain readable contrast; don't rely on colour alone for status.
- Keep touch targets around 44×44 px or larger.
- Support system text scaling where possible.
- Mobile-first layout; on tablet/desktop, use a centered max-width content area and optional sidebar.
- Keep navigation and spacing consistent across every screen.
