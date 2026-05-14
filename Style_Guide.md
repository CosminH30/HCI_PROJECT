# GAMAR Visual Style Guide

---

## Overview

GAMAR is a gaming stats tracker with a dark, high-contrast visual language built around competitive gaming culture. The design is assertive and data-forward. Every decision prioritizes legibility of numbers and fast scanning, while the aesthetic keeps the whole thing from feeling like a generic dashboard. Think military HUD crossed with esports broadcast graphics.

---

## Color

The palette is tight. There are three colors and you should not need more than that for any screen in the app.

**Background: `#1A1A1F`**
A very dark near-black with a slight cool undertone. Not pure black. This keeps the interface from feeling harsh while still reading as dark mode.

**Surface / Card: `#242428`**
Used for cards, panels, and any container that needs to sit slightly above the background. The contrast between this and the background is intentional but subtle.

**Accent: `#E8003D`**
The red. This is the only expressive color in the system and it has to work hard. It signals selection, importance, and brand. Never dilute it with transparency except in very specific hover states.

**Text Primary: `#FFFFFF`**
Pure white for all primary text values. Stat numbers, usernames, anything the user needs to read first.

**Text Secondary: `#7A7A8A`**
Muted gray for labels, subtitles, and rank indicators. Quiet enough not to compete with values but legible enough to read without squinting.

**Text Accent: `#E8003D`**
The red pulls double duty as a text color for featured stats like Total Kills and K/D Ratio. Not every number gets this treatment, just the ones that deserve emphasis.

---

## Typography

The typeface is all-caps, condensed, and aggressive everywhere that branding or navigation is involved. It loosens up for data values.

**Brand / Wordmark**
All-caps, wide letter-spacing (around 0.1em or more), bold weight, red. The name GAMAR should always feel like it is shouting at you calmly.

**Section Labels and UI Labels**
All-caps, tracked out (letter-spacing 0.12 to 0.15em), small size (10-11px), medium weight, white or muted gray depending on hierarchy. Examples: SELECT GAME, PLAYER PROFILE, TOTAL KILLS. These are never mixed case.

**Stat Values**
Large, bold, numerals. Somewhere between 28px and 36px depending on context. The primary stats use red, secondary stats use white. Never italic.

**Player Name**
Mixed case, medium to semibold, white, approximately 18-20px. This is the only place in the UI where we drop out of all-caps.

**Rank / Subtitle**
Mixed case, regular weight, secondary gray, 13-14px. Sits directly below the player name.

**Navigation Labels**
All-caps, small (10-11px), regular weight. Active state uses red, inactive uses secondary gray.

---

## Spacing and Layout

The layout is structured on a consistent base unit of 8px. Most padding inside cards is 16-24px. Gaps between stat cells use 16px. Do not break this rhythm without a good reason.

Cards and panels have no border radius, or an extremely subtle one (2-3px maximum). Sharp corners are part of the identity. Rounded corners would feel wrong here.

Stat data is displayed in a two-column grid inside cards. Left and right values are center-aligned within their column. Labels sit above values, not below.

---

## Component Notes

**Game Selector Tabs**
Two-option tab bar. The inactive tab is transparent with no border and muted gray text. The active tab has a solid red fill with white text. No border radius or very minimal (4px at most). The transition between states should snap, not animate softly.

**Player Profile Card**
Has a distinctive corner bracket decoration in red at all four corners. These are L-shaped marks, not full borders. The card sits against the background with the slightly elevated surface color. A horizontal red divider separates the avatar row from the stats grid.

**Avatar**
Circular, sized around 56-60px. Background is red with white initials in it. If a photo is present, the circle clips it. The initials fallback should always use the accent red.

**Status Pill (Online / Offline)**
Pill-shaped badge in the top right of the screen. Dark background, wifi icon, small all-caps label. When online, use white or a very subtle green. Do not use the red here since it would compete with the brand.

**Bottom Navigation Bar**
Solid dark background, four icon-and-label pairs. Active item uses the red accent. Inactive items use secondary gray. Icons are outlined/stroke style, not filled, except for the active Home state which appears filled in the screenshot. Consistent 24px icon size.

**Stat Quick-View Cards**
Smaller card blocks below the main profile. Full-width or half-width. Large number in red, small label in secondary gray below it. Minimal internal padding, dense but not cramped.

---

## Borders and Decorative Elements

The app uses very little decoration, but what it does use is precise. The corner brackets on the Player Profile card are the main decorative element and they carry a lot of weight. They reference targeting reticles and HUD elements from first-person shooter games. Do not overuse this pattern. It should appear on the main content card, not on every surface.

Dividers are 1px, red, and used sparingly. One divider inside the profile card is enough.

---

## Tone and Personality

The visual language is serious and data-focused. It does not try to be playful or friendly. It respects the user as a competitive player who wants information fast. Every design decision should answer the question: does this make the data easier to read? If not, it should not be there.

The red is the personality. Outside of the accent color, everything exists to make numbers legible.
