---
name: landing-page-skill
description: Generates a premium, high-converting, human-centric landing page for an AI/SaaS product using React + TypeScript, aligned with existing product UI and inspired by top-tier modern landing pages.
disable-model-invocation: true
---

# Landing Page Skill

This skill generates a production-ready, conversion-optimized landing page for an AI/SaaS product using React + TypeScript.

It combines:

Human-centered design

Modern SaaS UI patterns (Cardboard AI, Linear, Vercel, Notion)

Clean frontend architecture

High-quality product storytelling

The result should feel like a real, premium product landing page, not a generic template.

---

## When to Use

- Building a landing page for an AI or SaaS product
- Redesigning an existing marketing page
- Aligning landing page UI with product UI
- Converting product documentation into a marketing site
- Creating investor/demo-ready landing pages

---

## Core Philosophy

- Clarity > Cleverness
- Simplicity > Noise
- Trust > Hype
- Consistency > Novelty

The landing page should:

* Explain the product in under 5 seconds
* Build trust quickly
* Guide the user toward action

---

## Instructions

### 1. Understand the Product First

Before generating anything, extract:
- Target audience (developer, merchant, founder, enterprise, etc.)
- Core problem
- Key value proposition (transformation)
- Top 3 differentiators
- Product category (tool, infra, plugin, AI assistant, etc.)

If unclear → **ask clarifying questions FIRST**

---

### 2. Maintain UI Consistency

- Carefully study the existing product UI (if provided)
- Match:
  - Color palette
  - Typography style
  - Spacing system
  - Border radius and shadows
  - Component patterns

The landing page should feel like a **natural extension of the product**, not a separate design.

---

### 3. Follow Human-Centered Design Principles

- Focus on clarity over cleverness
- Avoid jargon unless user persona expects it
- Use real-world language, not buzzwords
- Emphasize:
  - Cognitive ease
  - Visual hierarchy
  - Accessibility
  - Emotional resonance

Every section should answer:
> “Why should I care?”

---

### 4. Structure the Landing Page

Generate the page with the following sections:

#### Hero Section
- Clear, bold headline (outcome-focused)
- Supporting subtext (what + who + why)
- Primary CTA (single, obvious action)
- Optional secondary CTA
- Visual: product UI mock or contextual usage

#### Social Proof
- Logos, testimonials, or metrics

#### Problem Section
- Clearly articulate user pain points

#### Solution Section
- Introduce the product naturally

#### Features / Capabilities
- 3–6 key features (title + explanation)

#### How It Works
- 3–4 simple steps

#### Product Showcase
- Real UI usage

#### Pricing / Plans (if applicable)

#### Final CTA Section

#### Footer

---

### 5. Vite + React + TypeScript Implementation (CRITICAL)

All generated code MUST follow these rules:

#### Tech Stack
- React (Functional Components only)
- TypeScript (strict typing)
- Prefer Next.js-compatible structure (no browser-only hacks)
- Tailwind CSS (preferred) OR match existing styling system
- Vite (build tool)
- Lenis (Smooth Scrolling)
- GSAP (Regular and Scroll-Triggered Animations)

---

#### Component Architecture

- Break UI into reusable components:
  - `HeroSection`
  - `FeatureCard`
  - `PricingCard`
  - `Navbar`
  - `Footer`
  - `CTASection`

- Use a **section-based architecture**, not one giant file

Folder / Component Structure

Use modular architecture:

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

#### TypeScript Rules

- Always define explicit types/interfaces

Example:
```ts
type Feature = {
  title: string;
  description: string;
  icon?: React.ReactNode;
};
```

#### Anti-Patterns (DO NOT DO)

- No monolithic components
- No `any` in TypeScript
- No generic templates
- No excessive animations
- No buzzword-heavy copy
- No inconsistent spacing
- No ignoring product UI

#### Final Quality Checklist

Before returning output:

- Is the value clear in 5 seconds?
- Is UI consistent with product?
- Is code production-ready?
- Is TypeScript strict and clean?
- Is UX intuitive?

If not → refine

## End Goal

The output should feel like it was created by:

- A top-tier product designer
- A senior frontend engineer
- A conversion-focused marketer

Not an AI.