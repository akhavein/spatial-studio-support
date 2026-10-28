---
name: "spatial-studio-support"
description: "Source capture of the existing implementation; no new visual direction."
colors: {"ink":"#17201c","paper":"#f5f5ef","paper-deep":"#ebece4","surface":"#ffffff","line-strong":"#aab6ad","accent":"#087f5b","accent-deep":"#075f46","accent-pale":"#dff3e9","blueprint":"#163d58","blueprint-line":"#80aec5","warning":"#8b4c16","warning-pale":"#fff0dc"}
---

# Design System: spatial-studio-support

## Overview

This is a source capture of the incumbent implementation at `f3e84b31150202913fc796f424cdbf96685b3514`, not a redesign or a claim that the interface has been rendered or tested. Source files remain the implementation authority. Creative metaphors, qualitative branding and unverified component previews are deliberately unresolved.

The full declaration inventory, selector/variant scope, file locations and source hashes are in `.impeccable/design-source.json`. Re-capture after relevant implementation changes; do not apply an isolated declaration outside its original selector, media query or platform.

## Colors

Representative observed declarations (complete source context remains in the inventory):

- `styles.css:3` — `:root`: `--ink: #17201c`.
- `styles.css:7` — `:root`: `--surface: #ffffff`.
- `styles.css:10` — `:root`: `--accent: #087f5b`.
- `styles.css:37` — `body`: `background: radial-gradient(circle at 85% 4%, rgba(8, 127, 91, 0.1), transparent 30rem),
    var(--paper)`.
- `styles.css:40` — `body`: `color: var(--ink)`.
- `styles.css:54` — `a`: `color: var(--accent-deep)`.
- `styles.css:60` — `a:hover`: `color: var(--accent)`.
- `styles.css:77` — `.skip-link`: `background: var(--ink)`.
- `styles.css:78` — `.skip-link`: `color: #fff`.
- `styles.css:84` — `.skip-link:focus`: `color: #fff`.
- `styles.css:98` — `.site-header`: `background: rgba(245, 245, 239, 0.92)`.
- `styles.css:115` — `.brand`: `color: var(--ink)`.
- `styles.css:123` — `.brand:hover`: `color: var(--ink)`.
- `styles.css:132` — `.brand-mark`: `background: var(--blueprint)`.
- `styles.css:140` — `.brand-mark::before,
.brand-mark::after`: `background: #bcebd8`.
- `styles.css:164` — `.site-nav a`: `color: var(--ink-soft)`.

## Typography

Representative observed declarations (complete source context remains in the inventory):

- `styles.css:41` — `body`: `font-family: ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif`.
- `styles.css:42` — `body`: `font-size: 1rem`.
- `styles.css:43` — `body`: `line-height: 1.65`.
- `styles.css:116` — `.brand`: `font-weight: 760`.
- `styles.css:117` — `.brand`: `letter-spacing: -0.025em`.
- `styles.css:165` — `.site-nav a`: `font-size: 0.93rem`.
- `styles.css:166` — `.site-nav a`: `font-weight: 650`.
- `styles.css:197` — `.eyebrow`: `font-size: 0.78rem`.
- `styles.css:198` — `.eyebrow`: `font-weight: 780`.
- `styles.css:199` — `.eyebrow`: `letter-spacing: 0.13em`.
- `styles.css:200` — `.eyebrow`: `line-height: 1.3`.
- `styles.css:216` — `h1,
h2,
h3`: `line-height: 1.08`.
- `styles.css:223` — `h1`: `font-size: clamp(3rem, 7vw, 6.2rem)`.
- `styles.css:224` — `h1`: `letter-spacing: -0.065em`.
- `styles.css:229` — `h2`: `font-size: clamp(2rem, 4.5vw, 3.4rem)`.
- `styles.css:230` — `h2`: `letter-spacing: -0.045em`.

## Layout

Representative observed declarations (complete source context remains in the inventory):

- `styles.css:36` — `body`: `margin: 0`.
- `styles.css:49` — `img,
svg`: `display: block`.
- `styles.css:50` — `img,
svg`: `max-width: 100%`.
- `styles.css:75` — `.skip-link`: `padding: 0.65rem 0.9rem`.
- `styles.css:90` — `.container`: `margin-inline: auto`.
- `styles.css:105` — `.nav-shell`: `display: flex`.
- `styles.css:108` — `.nav-shell`: `gap: 1.5rem`.
- `styles.css:112` — `.brand`: `display: inline-flex`.
- `styles.css:114` — `.brand`: `gap: 0.7rem`.
- `styles.css:156` — `.site-nav`: `display: flex`.
- `styles.css:158` — `.site-nav`: `gap: 0.25rem`.
- `styles.css:162` — `.site-nav a`: `padding: 0.5rem 0.72rem`.
- `styles.css:181` — `.hero`: `padding: clamp(4rem, 9vw, 7.5rem) 0 clamp(3.5rem, 8vw, 6rem)`.
- `styles.css:185` — `.hero-grid`: `display: grid`.
- `styles.css:186` — `.hero-grid`: `grid-template-columns: minmax(0, 1.08fr) minmax(20rem, 0.92fr)`.
- `styles.css:188` — `.hero-grid`: `gap: clamp(2.5rem, 7vw, 6.5rem)`.

## Elevation & Depth

Representative observed declarations (complete source context remains in the inventory):

- `styles.css:17` — `:root`: `--shadow: 0 22px 70px rgba(23, 32, 28, 0.12)`.
- `styles.css:67` — `:focus-visible`: `box-shadow: 0 0 0 6px var(--ink)`.
- `styles.css:133` — `.brand-mark`: `box-shadow: inset 0 0 0 1px rgba(255, 255, 255, 0.14)`.
- `styles.css:146` — `.brand-mark::before`: `box-shadow: 0 0.48rem 0 #bcebd8, 0 0.96rem 0 #bcebd8`.
- `styles.css:152` — `.brand-mark::after`: `box-shadow: 0.48rem 0 0 #bcebd8, 0.96rem 0 0 #bcebd8`.
- `styles.css:272` — `.button`: `box-shadow: 0 5px 18px rgba(23, 32, 28, 0.06)`.
- `styles.css:323` — `.studio-card`: `box-shadow: var(--shadow)`.
- `styles.css:534` — `.card`: `box-shadow: 0 10px 34px rgba(23, 32, 28, 0.04)`.
- `styles.css:629` — `.band .button`: `box-shadow: none`.
- `styles.css:767` — `details[open]`: `box-shadow: 0 8px 26px rgba(23, 32, 28, 0.05)`.
- `styles.css:853` — `.support-panel`: `box-shadow: var(--shadow)`.

## Shapes

Representative observed declarations (complete source context remains in the inventory):

- `styles.css:18` — `:root`: `--radius-sm: 0.75rem`.
- `styles.css:19` — `:root`: `--radius-md: 1.15rem`.
- `styles.css:20` — `:root`: `--radius-lg: 1.75rem`.
- `styles.css:66` — `:focus-visible`: `border-radius: 0.25rem`.
- `styles.css:76` — `.skip-link`: `border-radius: 0.55rem`.
- `styles.css:97` — `.site-header`: `border-bottom: 1px solid rgba(170, 182, 173, 0.72)`.
- `styles.css:131` — `.brand-mark`: `border-radius: 0.55rem`.
- `styles.css:163` — `.site-nav a`: `border-radius: 0.55rem`.
- `styles.css:265` — `.button`: `border: 1px solid var(--line-strong)`.
- `styles.css:266` — `.button`: `border-radius: 0.7rem`.
- `styles.css:276` — `.button:hover`: `border-color: var(--accent)`.
- `styles.css:282` — `.button.primary`: `border-color: var(--accent)`.
- `styles.css:288` — `.button.primary:hover`: `border-color: var(--accent-deep)`.
- `styles.css:312` — `.hero-note span::before`: `border-radius: 50%`.
- `styles.css:320` — `.studio-card`: `border: 1px solid rgba(128, 174, 197, 0.32)`.
- `styles.css:321` — `.studio-card`: `border-radius: var(--radius-lg)`.

## Components

Representative observed declarations (complete source context remains in the inventory):

- `styles.css:64` — `:focus-visible`: `outline: 3px solid #ffbf47`.
- `styles.css:65` — `:focus-visible`: `outline-offset: 3px`.
- `styles.css:80` — `.skip-link`: `transition: transform 140ms ease`.
- `styles.css:1024` — `@media (prefers-reduced-motion: reduce) > *,
  *::before,
  *::after`: `transition-duration: 0.01ms`.
- `styles.css:1025` — `@media (prefers-reduced-motion: reduce) > *,
  *::before,
  *::after`: `animation-duration: 0.01ms`.
- `styles.css:1026` — `@media (prefers-reduced-motion: reduce) > *,
  *::before,
  *::after`: `animation-iteration-count: 1`.

## Do's and Don'ts

- Preserve existing tokens, selectors, light/dark variants, locale overrides and platform semantics.
- Reuse existing component implementations and inspect their complete interaction states.
- Verify accessibility, navigation, focus, text scaling and reduced motion in the appropriate browser or native runtime before claiming a UI pass.
- Do not treat this source inventory as a rendered audit or approval for a new brand.
- Do not synthesize missing colors, scales, component previews or product claims.
