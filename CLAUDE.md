# W'sup design rules

Work happens in the Claude Design canvas "W'sup Canvas" (https://claude.ai/artifact/4Bf57Mhecb76ydfPbWZpdp), not in separate HTML files.

## Visual hierarchy (always)
Every screen follows a strict type hierarchy. Each level is clearly smaller than the one above it:
1. Screen headline (e.g. "What do you feel like doing?"): the largest text, 40px Tan Memories.
2. Content titles inside modules (banner titles): 26px.
3. Section headings (e.g. "Happening around you"): 24px.
4. Item content (intents in cards, e.g. "Padel after work, anyone?"): 17px.
5. Meta and labels (names, area, time, counts): 12.5–13px Hanken Grotesk.
Never let a section heading or an item match or beat the level above it. Check this before publishing any screen.

## App colour
- Page background: dull white #f4f4f0, not cream.
- Secondary surfaces (top banner area, selected cards): #e9e9e3. Cards and inputs: #fff.
- Dark green #284732 is for CTAs (buttons) and the bottom navbar only, never as a surface.
- Orange #ff8a2b for small accents (live dots, active carousel dot).

## App layout
- Bottom nav: floating capsule, hides on scroll down, returns on scroll up.
- The "what do you feel like doing" input stays fixed above the nav.
- Home banners: one banner visible at a time, filled with design-system illustrations, dots below.
