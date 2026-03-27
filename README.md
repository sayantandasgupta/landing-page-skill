# 🚀 landing-page-skill

A Cursor Agent Skill that generates **premium, high-converting, human-centric landing pages** for AI and SaaS products — directly from your product's technical documentation.

Available on [skills.sh](https://skills.sh) · Works with Cursor, Claude Code, Windsurf, and 17+ agents.

---

## ✨ What It Does

Give this skill your product documentation, and it will generate a **production-ready landing page** built with React + TypeScript — one that feels like it was designed by a product designer, engineered by a senior frontend developer, and written by a conversion-focused marketer.

It combines:

- **Human-centered design** — clarity over cleverness, trust over hype
- **Modern SaaS UI patterns** — inspired by Linear, Vercel, Notion, and Cardboard AI
- **Clean frontend architecture** — modular, strict TypeScript, Tailwind CSS
- **High-quality product storytelling** — copy that explains your product in under 5 seconds

The result is not a generic template. It's a landing page that feels native to your product.

---

## 🧠 Core Philosophy

```
Clarity > Cleverness
Simplicity > Noise
Trust > Hype
Consistency > Novelty
```

Every section is designed to answer one question: **"Why should I care?"**

---

## 📦 Installation

### Via skills.sh (recommended)

```bash
npx skills add <your-username>/landing-page-skill
```

This installs the skill into your project's `.cursor/skills/` folder and makes it available to Cursor's agent automatically.

### Manual Installation

1. Clone this repository or download `SKILL.md`
2. Place it inside your project at:

```
.cursor/
  skills/
    landing-page-skill/
      SKILL.md
```

3. Cursor will detect and load the skill automatically on the next agent session.

---

## 🛠️ How to Use

Once installed, open Cursor's agent and describe your task in natural language. The skill activates automatically when the context matches.

**Example prompts:**

```
Build a landing page for this product based on the documentation in /docs
```

```
Generate a landing page for our SaaS tool. Match the UI style of the existing product.
```

```
Create an investor-ready landing page from this README and product spec.
```

The agent will:
1. Read and analyze your product documentation
2. Extract the target audience, value proposition, and key differentiators
3. Study your existing product UI (if provided) to match design language
4. Generate a full, modular landing page with all standard sections

---

## 🗂️ Generated Page Structure

The skill produces a complete landing page with the following sections:

| Section | Description |
|---|---|
| **Hero** | Bold outcome-focused headline, subtext, primary CTA, optional visual |
| **Social Proof** | Logos, testimonials, or key metrics |
| **Problem** | Clearly articulated user pain points |
| **Solution** | Natural product introduction |
| **Features** | 3–6 key capabilities with titles and explanations |
| **How It Works** | 3–4 step walkthrough |
| **Product Showcase** | Real UI usage or contextual visuals |
| **Pricing** | Plans and tiers (if applicable) |
| **Final CTA** | Closing conversion section |
| **Footer** | Standard footer with navigation |

---

## ⚙️ Tech Stack

All generated code follows these conventions:

- **React** — Functional components only
- **TypeScript** — Strict typing, no `any`
- **Tailwind CSS** — Utility-first styling (or matches your existing system)
- **Vite** — Build tooling
- **GSAP** — Scroll-triggered animations
- **Lenis** — Smooth scrolling

### Component Architecture

The skill enforces a modular folder structure:

```
/components
  /layout
    Navbar.tsx
    Footer.tsx
  /sections
    HeroSection.tsx
    ProblemSection.tsx
    FeaturesSection.tsx
    PricingSection.tsx
    CTASection.tsx
  /ui
    Button.tsx
    FeatureCard.tsx
    PricingCard.tsx
```

---

## ✅ Quality Checklist

Before returning output, the skill self-evaluates against:

- [ ] Is the value proposition clear within 5 seconds?
- [ ] Is the UI consistent with the existing product design?
- [ ] Is the code production-ready and TypeScript-strict?
- [ ] Is the UX intuitive and accessible?

If any check fails — it refines before responding.

---

## 🚫 Anti-Patterns (What This Skill Avoids)

- ❌ Monolithic components
- ❌ `any` in TypeScript
- ❌ Generic, template-like output
- ❌ Excessive or distracting animations
- ❌ Buzzword-heavy marketing copy
- ❌ Inconsistent spacing or layout
- ❌ Ignoring existing product UI

---

## 🤝 Contributing

Found a way to make this skill better? PRs are welcome.

If you improve the skill for a specific use case (e.g. developer tools, e-commerce SaaS, B2B enterprise), consider opening a PR or forking it as a variant.

---

## 📄 License

MIT — free to use, modify, and distribute.

---

*Built by [Sayantan](https://github.com/your-username) at [Renben Technologies](https://renben.tech)*