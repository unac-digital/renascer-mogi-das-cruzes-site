---
name: Igreja Renascer em Cristo — Mogi das Cruzes
description: Sistema institucional “Fios de encontro” para uma presença digital acolhedora e transparente.
colors:
  indigo-deep: "#14133a"
  ink: "#171637"
  cobalt: "#394ee8"
  coral: "#ef6255"
  marigold: "#f2b838"
  mineral-paper: "#f2f4f3"
  white: "#ffffff"
  muted-ink: "#5e5c70"
  line: "#cbc8bc"
typography:
  display:
    fontFamily: "Bricolage Grotesque, Segoe UI, sans-serif"
    fontSize: "clamp(3.2rem, 7.2vw, 6rem)"
    fontWeight: 700
    lineHeight: 0.91
    letterSpacing: "-0.04em"
  headline:
    fontFamily: "Bricolage Grotesque, Segoe UI, sans-serif"
    fontSize: "clamp(2.2rem, 4.6vw, 4.6rem)"
    fontWeight: 700
    lineHeight: 0.98
    letterSpacing: "-0.035em"
  body:
    fontFamily: "Bricolage Grotesque, Segoe UI, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: "normal"
  label:
    fontFamily: "Bricolage Grotesque, Segoe UI, sans-serif"
    fontSize: "0.78rem"
    fontWeight: 700
    lineHeight: 1.3
    letterSpacing: "0.035em"
rounded:
  square: "0"
spacing:
  gutter: "clamp(1.25rem, 4vw, 4rem)"
  section: "clamp(5rem, 9vw, 8rem)"
components:
  button-primary:
    backgroundColor: "{colors.indigo-deep}"
    textColor: "{colors.white}"
    rounded: "{rounded.square}"
    padding: "0.85rem 1rem 0.85rem 1.25rem"
    height: "54px"
  button-primary-hover:
    backgroundColor: "{colors.cobalt}"
    textColor: "{colors.white}"
  button-light:
    backgroundColor: "{colors.white}"
    textColor: "{colors.indigo-deep}"
    rounded: "{rounded.square}"
    padding: "0.85rem 1rem 0.85rem 1.25rem"
    height: "54px"
---

# Design System: Igreja Renascer em Cristo — Mogi das Cruzes

## Overview

**Creative North Star: “Fios de encontro”**

The system uses intersecting bands as a durable language for presence, encounter, and clear routes. Large typographic statements sit beside constructed abstract fields rather than stock religious imagery. The overall tone is contemporary and institutional, with calm reading surfaces punctuated by decisive color.

Density varies by section: generous openings, structured lists, and compact status panels. The identity comes from overlap, directional movement, and square-notched geometry—not from decorative symbols or an unapproved church mark.

**Key Characteristics:**
- High-contrast indigo and cobalt fields balanced by cool mineral white.
- Coral and marigold bands used as structural intersections.
- Oversized, tightly set Bricolage Grotesque headlines.
- Mostly square geometry with one clipped upper-right notch.
- Explicit status language for pending or unconfirmed information.

## Colors

A full palette gives each large section a distinct field while preserving a single high-contrast visual voice.

### Primary
- **Deep Indigo:** The institutional anchor for the masthead, purpose section, footer, and primary controls.
- **Cobalt:** The action field and the principal expressive accent in woven compositions.

### Secondary
- **Marigold:** Warm connective bands, emphasis fields, and hover feedback.
- **Coral:** Counterpoint bands and small state markers.

### Neutral
- **Mineral Paper:** The cool page field and pale content surface.
- **White:** Reading planes and text on saturated fields.
- **Ink:** Primary text and fine structural rules.
- **Muted Ink:** Supporting copy on pale surfaces.
- **Line:** Quiet separators and framed structures.

### Named Rules

**The Field Rule.** Color owns complete regions or intersecting bands; it is not sprinkled as disconnected decoration.

**The Truth-State Rule.** Pending information is signaled with coral outlined squares and plain language, never hidden in low-contrast fine print.

## Typography

**Display Font:** Bricolage Grotesque (with Segoe UI and sans-serif fallback)
**Body Font:** Bricolage Grotesque (with Segoe UI and sans-serif fallback)

**Character:** One variable grotesque provides both expressive width and a clear, accessible reading voice. Contrast comes from scale, weight, and measure rather than from mixing unrelated typefaces.

### Hierarchy
- **Display** (700, fluid 3.2–6rem, 0.91): hero statements only, balanced into short lines.
- **Headline** (700, fluid 2.2–4.6rem, 0.98): section openings with a maximum measure around 12 characters.
- **Title** (650–700, 1.5–1.7rem): list and status headings.
- **Body** (400, 1rem, 1.6): general reading copy, capped near 65 characters where practical.
- **Label** (700, 0.78rem, 0.035em): short preview and location markers; sentence case is preferred.

### Named Rules

**The Short-Line Rule.** Display copy stays compact and balanced; body copy carries explanation at a calmer measure.

## Layout

Content is contained within a 1240px maximum width with a fluid gutter. Desktop openings use asymmetric two-column grids; subsequent sections shift between two-column narrative blocks and structured lists. Section padding is generous and fluid. At 920px navigation becomes a disclosure menu. At 680px every content grid becomes a single column, the hero artwork expands to the viewport edges, and copy precedes art.

**The Crossing Rule.** Major layouts pair a stable reading column with a directional or structured counterweight rather than two equal card columns.

## Elevation & Depth

The system is flat by default. Depth appears only where one plane materially sits above another: the hero’s framed white field and primary controls use soft, offset ambient shadows. Section separation relies on color fields and fine rules rather than stacked cards.

### Shadow Vocabulary
- **Framed plane:** `18px 22px 46px rgba(23,22,55,.1)` for the hero’s white construction field.
- **Raised control:** `0 10px 24px rgba(20,19,58,.18)` for primary actions.

## Shapes

Corners are square. The recurring exception is a clipped upper-right notch on primary controls and the pending-information panel, made with a simple five-point polygon. Fine 1px rules frame artwork and separate list rows. Colored bands use straight edges, diagonal transforms, and controlled overlap.

## Components

### Buttons
- **Shape:** Square with a 15px clipped upper-right notch.
- **Primary:** Deep indigo with white text, minimum 54px height, generous horizontal spacing, and a line-drawn arrow.
- **Hover / Focus:** Cobalt or marigold field shift, 3px upward movement, and a 3px marigold focus outline offset by 4px.
- **Light:** White with indigo text on saturated section fields.

### Cards / Containers
- **Corner Style:** Square or clipped at one upper corner.
- **Background:** White or mineral paper against saturated fields.
- **Shadow Strategy:** Flat unless visibly layered in the hero.
- **Border:** Fine ink or neutral rules.
- **Internal Padding:** Fluid 1.5–3rem for status containers.

### Navigation
Desktop navigation is a compact horizontal row on deep indigo, with marigold underline feedback and a notched marigold WhatsApp action. Mobile navigation becomes a full-width indigo disclosure below the masthead; Escape closes it and returns focus to the trigger.

### Woven Field
Intersecting coral, marigold, cobalt, and indigo bands pass above and below a framed plane. Use it as a signature abstract construction, not as a logo. Motion is a single coordinated entrance and resolves immediately under reduced-motion preferences.

## Do's and Don'ts

### Do:
- **Do** use full color fields and deliberate overlap to create hierarchy.
- **Do** preserve cool pale grounds, strong contrast, and visible keyboard focus.
- **Do** use the clipped notch sparingly on primary actions or explicit status planes.
- **Do** keep unconfirmed institutional details visibly marked as pending.

### Don't:
- **Don't** present the three-bar brand treatment as an approved church logo.
- **Don't** add stock church imagery, ornamental stained-glass effects, gradients, or decorative religious symbols without approved assets.
- **Don't** turn content into rows of interchangeable rounded cards.
- **Don't** reduce labels or interactive copy below the established legibility floor.
