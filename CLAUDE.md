# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project

Standalone landing page for **STAK Digital** — local SEO and Google My Business specialists.
Single-file HTML project (`index.html`) with no build tools.

## Development

```bash
# Open in browser (no server needed for static assets)
open index.html         # macOS
xdg-open index.html     # Linux
```

No build step, no tests, no package manager. Edit `index.html` directly.

## Tech Stack

- Pure HTML, CSS, JavaScript — single `index.html` file
- Google Fonts and Font Awesome via CDN (only external dependencies)
- No frameworks, no bundler

## Brand Specs

| Token | Value |
|---|---|
| Primary blue | `#185FA5` |
| Growth green | `#1D9E75` |
| Neutral graphite | `#2C2C2A` |
| Light blue bg | `#E6F1FB` |
| WhatsApp green | `#25D366` |

Typography: Google Fonts — modern/professional style. Avoid Inter, Roboto, Arial.

Logo: Square rounded icon in `#185FA5` with "SK" in white. Text: "STAK" large spaced + "DIGITAL" smaller in blue below.

WhatsApp link: `https://wa.me/5512988300712` | Phone: `(12) 98830-0712`

## Page Sections (in order)

1. **Hero** — navbar with logo, headline "Seu negócio no topo do Google", subheadline, two CTAs (WhatsApp + scroll to form), geometric/gradient background
2. **Value Props** — 3 cards: SEO Local, Google Meu Negócio, Resultados Reais
3. **Audience** — 2 columns: local businesses + partner agencies
4. **Differentials** — 4 bullet points (personalized service, custom strategy, clear reports, specialized team)
5. **FAQ** — 8-item JS accordion (see questions below)
6. **CTA** — blue/green bg, "Pronto para aparecer no topo?", WhatsApp button + phone
7. **Contact Form** — Name, Email, WhatsApp, Business type, Message; button "Solicitar diagnóstico grátis" (visual only, no backend)
8. **Footer** — logo, phone, WhatsApp, copyright, tagline "Stephanie · Almeida · Kerber"
9. **Floating WhatsApp button** — fixed bottom-right, `#25D366`

## FAQ Questions

1. O que é SEO local e por que meu negócio precisa?
2. O que é Google Meu Negócio e como ele me ajuda?
3. Em quanto tempo vejo resultados?
4. Meu negócio é pequeno. Vale a pena investir em SEO?
5. Como funciona o trabalho da STAK Digital?
6. Vocês atendem agências de marketing?
7. Quanto custa o serviço?
8. Preciso ter site para trabalhar com vocês?

(Full answer text available in git history of this file, prior to the CLAUDE.md rewrite.)

## Key Implementation Notes

- Mobile-first, 100% responsive
- FAQ accordion in vanilla JS
- Scroll animations via Intersection Observer (fade-in, slide-up)
- Smooth scroll between sections
- Navbar background effect on scroll
- Gradient: subtle blend between `#185FA5` and `#1D9E75`
- Slogan: "Seu negócio no topo. Do mapa ao clique."
