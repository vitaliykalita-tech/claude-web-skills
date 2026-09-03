---
name: responsive-design
description: Build and optimize responsive websites that work correctly across desktop, tablet and mobile devices.
---

# Responsive Design

Every website must provide a polished and usable experience across desktop, tablet and mobile devices.

## Core principle

Do not simply shrink the desktop version.

Each layout should be intentionally designed for the available screen size.

## Screen sizes

Always consider at minimum:

- 1440px
- 1280px
- 1024px
- 768px
- 430px
- 390px
- 375px

These are reference sizes, not mandatory breakpoints.

## Mobile priority

Commercial websites are often viewed primarily on smartphones.

Pay special attention to:

- navigation
- menu
- typography
- buttons
- contact actions
- WhatsApp buttons
- forms
- images
- section spacing
- content density

Important actions must remain easy to access with one hand.

## Layout

Use flexible layouts whenever possible.

Prefer:

- CSS Grid
- Flexbox
- fluid widths
- max-width containers
- responsive typography
- appropriate spacing systems

Avoid excessive fixed widths and unnecessary device-specific hacks.

## Images

Check that images:

- do not stretch
- do not overflow
- maintain appropriate proportions
- crop correctly when using object-fit
- remain visually important on mobile

## Typography

Check:

- heading sizes
- paragraph sizes
- line height
- text wrapping
- long titles
- buttons containing long text

Do not allow text to become too small simply to fit the layout.

## Navigation

On smaller screens:

- navigation must remain usable
- menus must not overflow
- buttons must remain accessible
- important contact actions should remain visible

## Common problems to detect

Always check for:

- horizontal scrolling
- overflowing elements
- broken grids
- overlapping content
- text clipping
- buttons becoming too small
- navigation overflow
- images stretching
- excessive empty space
- sections becoming too narrow
- unexpected element movement

## Responsive behavior

When changing a component for mobile, consider whether the change affects desktop.

Do not fix mobile by breaking desktop.

Do not fix desktop by breaking mobile.

## Final verification

Before considering the website finished, verify:

### Desktop

- layout
- navigation
- typography
- images
- spacing
- buttons

### Tablet

- layout transitions
- grids
- navigation
- spacing
- typography

### Mobile

- navigation
- content order
- buttons
- forms
- images
- typography
- spacing
- horizontal overflow

The final result should look intentionally designed at every major screen size, not like a desktop website compressed into a phone.
