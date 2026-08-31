# Mint Nails Studio Design System

## Direction

A quiet, high-end spa experience: restrained, spacious, precise, and welcoming. Photography, typography, and service clarity lead; mint is used as a controlled brand accent rather than constant decoration.

## Color

- Brand mint: `#45D6BD`, used as a committed surface color
- Bright mint: `#73EED8`, reserved for detail on deep backgrounds
- Deep green: `#063C38`, primary ink and dark canvas
- True off-white: `#FDFDFB`, neutral surface
- Mint mist: `#EAF8F5`, secondary surface

The palette is locked across the full site: off-white for breathing room, mint for brand-led moments, and deep green for contrast and practical information. No unrelated accent colors are introduced.

## Typography

Prata is reserved for display typography, echoing the refined serif character already present in the studio logo. Manrope handles navigation, body copy, prices, and practical information. Display tracking never exceeds `-0.04em`.

## Composition

- Asymmetric hero with a softly framed photographic plane
- Airy service tiles with a consistent 16px radius
- Deep-green price canvas with sticky introduction on desktop
- Tight photographic gallery with unequal columns
- Mint statement surfaces alternating with off-white and deep green
- A restrained shape system: 14px content surfaces and pill-shaped controls
- One shared spacing, radius, button, and interaction language from navigation through footer

## Motion

Motion communicates hierarchy and feedback: an orchestrated hero entrance, scroll progress, image depth, staggered content reveals, tactile hover states, menu choreography, and lightbox transitions. All motion uses exponential easing and is removed or reduced under `prefers-reduced-motion`.

## Responsive Behavior

At mobile widths the poster becomes a sequential text and image composition, service rows retain their index structure, price columns stack, gallery remains two columns, and call/map actions become a fixed bottom bar.
