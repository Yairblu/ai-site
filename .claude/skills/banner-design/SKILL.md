# Banner Design Skill Overview

This is a multi-format banner creation system built on Claude's Agent SDK. It handles social media covers, ad banners, website heroes, and print assets—but explicitly excludes video editing, full website design, and print production.

## Core Workflow

The skill follows a structured five-step process:

1. **Requirements gathering** via user questions about purpose, platform, content, branding, style preferences, and desired quantity
2. **Research and art direction** using design intelligence and Pinterest reference searches
3. **Design and visual generation** combining HTML/CSS templates with AI-generated visuals
4. **Export to images** using screenshot automation at exact platform dimensions
5. **Presentation and iteration** based on user feedback

## Key Technical Details

The system supports 10+ art direction styles (minimalist, gradient, bold typography, neon, glassmorphism, etc.) and uses two AI image generation models:

- **Standard (Gemini Flash)**: Fast 2K backgrounds and patterns
- **Pro (Gemini 3 Pro)**: Detailed 4K hero illustrations and complex artwork

Size specifications cover major platforms—Twitter headers at 1500×500px, Instagram stories at 1080×1920px, YouTube channel art at 2560×1440px, and more.

## Design Constraints

Banners follow strict guidelines: critical content in the central 70-80% safe zone, maximum two typefaces, single CTA per banner, 4.5:1 contrast ratio for accessibility, and text under 20% of ad space to comply with platform policies.
