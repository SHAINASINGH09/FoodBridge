# FoodBridge

A one-page homepage for **FoodBridge**, a social-impact platform that connects food donors (restaurants, hotels, caterers, households) with NGOs and community kitchens. Built for the **AI Prompt Battle by OSCode**.

**Live site:** https://foodbridge-iota-seven.vercel.app
**Repository:** https://github.com/SHAINASINGH09/foodbridge  

## The problem

Surplus food is thrown away in one place while people go without meals in another, and the two sides rarely meet. FoodBridge is the bridge between them: it matches surplus food to the nearest verified NGO and arranges a volunteer pickup.

## What the page includes

| Section | What it does |
|---|---|
| Hero | Headline, call to action, animated "bridge" graphic and an interactive **List surplus food** widget that matches a donation to a nearby NGO |
| The Problem | A 45-plate visual (one in three plates wasted) and three headline statistics |
| Our Solution | Explains the platform for donors, NGOs and neighbours |
| How It Works | Four-step donation process |
| Key Features | Easy donation, verified NGO partners, pickup coordination, community participation |
| Impact | Animated bars and counters (illustrative sample data) |
| Community Stories | Three illustrative testimonials from a donor, an NGO and a volunteer |
| Call to Action | Tabs for Donate food, Volunteer and Partner, with a validated sign-up form |
| Footer | Navigation and contact details |

## Design decisions

- **Concept:** the bridge. Donor and NGO sit at either end of an arc, and the idea returns in the hero graphic and the widget's match result.
- **Palette:** leaf green `#2E7D4F`, saffron `#F2A104`, beetroot `#7E1F42` (problem section), deep forest `#0F2A1B` and a near-white background. The beetroot section is the one deliberately heavy, high-contrast moment.
- **Typography:** Bricolage Grotesque for headlines and Instrument Sans for body text.
- **Interaction:** the hero widget, the animated impact counters (they run once, on scroll) and the Donate / Volunteer / Partner tabs.
- **Accessibility:** keyboard-visible focus states, ARIA labels on interactive controls, light and dark mode support, and reduced-motion support.
- **Responsive:** tested layouts for desktop, tablet and mobile using CSS Grid and flexbox.

## How I used AI

1. **Brief to plan.** I gave the full challenge brief to Claude and asked for a design plan before any code: palette, type, layout concept and principles. I asked it to avoid generic AI-looking defaults (cream and terracotta, all-caps labels, identical card grids).
2. **Plan to build.** Claude wrote the whole page as one self-contained HTML file with no framework and no build step, so it deploys anywhere.
3. **Content.** Claude wrote realistic Delhi-based copy, sample NGO names and illustrative stories. The statistics in The Problem section come from UNEP and FAO figures. Check the current numbers before relying on them.
4. **Iteration.** *(Add your own: what you asked Claude to change, and why.)*

## Illustrative content

The impact numbers, testimonials, NGO names and contact details are **sample content** for this concept. They are labelled as illustrative on the page.

## Run locally

No install needed. Open `index.html` in a browser.

## Deploy

**Vercel:** import this repo, keep the framework preset as **Other**, leave the build command empty and deploy.
**Render:** create a **Static Site** from this repo, leave the build command empty and set the publish directory to `.`.

## Project structure

```
foodbridge/
├── index.html   # the entire site (HTML, CSS and JS)
└── README.md
```

## Tech

HTML, CSS and vanilla JavaScript. Google Fonts. No dependencies.

---

Built by SHAINA SINGH for the OSCode AI Prompt Battle.
