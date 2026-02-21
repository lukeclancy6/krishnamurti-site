# Krishnamurti Personal Website

A personal website in the voice and spirit of Jiddu Krishnamurti. The site enacts his teaching: no authority, no follower-making, just an invitation to look for yourself. The paradox is played completely straight.

Built with [Astro](https://astro.build). Zero client-side JavaScript except for the passage flipper, rotating homepage quote, and random page navigation.

## Pages

| Route | Title |
|-------|-------|
| `/` | Why Are You Here? |
| `/on` | On… |
| `/life` | A Life |
| `/dialogues` | Dialogues |
| `/passages` | Passages |
| `/reading` | What He Read |
| `/questions` | Questions |

## Stack

- **Framework**: Astro 5
- **Styling**: Pure CSS with custom properties — no Tailwind
- **Fonts**: Lora (display), EB Garamond (body), Cormorant SC (labels) — self-hosted via fontsource
- **Content**: Astro pages + TypeScript data file for passages

## Design

Ojai palette (`#FAF7F0` background, `#8B6914` gold accent, `#4A6741` green). Open, warm, and luminous — intentionally unlike the kind of ornate, authoritative design that would have made him uncomfortable.

No paper texture. No drop caps. No dog-eared corners. Hairline rules and `·  ·  ·` breath dividers instead of Victorian ornament. Portrait: Library of Congress / Bain Collection, public domain, `filter: grayscale(1) contrast(1.15) brightness(1.05)`.

## Development

```sh
npm install
npm run dev       # localhost:4321
npm run build
npm run preview
```
