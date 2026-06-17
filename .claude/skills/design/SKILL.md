# ckm:design Skill Overview

This is a comprehensive design system built on Claude's Agent SDK that handles multiple design disciplines under one unified skill.

## Core Capabilities

The skill manages **brand identity, design tokens, UI styling, logo generation, corporate identity programs, presentations, banners, icons, and social media imagery**. It routes tasks to appropriate sub-skills while maintaining cohesive design workflows.

## Key Features

**Logo Design:** Generates 55+ styles across 30 color palettes using Gemini AI, with industry-specific guidance.

**Corporate Identity (CIP):** Produces 50+ deliverables including business cards, letterhead, and branded materials via mockup generation.

**Banner Design:** Supports 22 art direction styles optimized for Facebook, Twitter, LinkedIn, YouTube, Instagram, Pinterest, and TikTok, with precise platform-specific dimensions.

**Social Photos:** Multi-platform image design converting HTML/CSS to exported screenshots at exact pixel dimensions.

**Icon Design:** Creates 15 SVG icon styles across 12 categories using Gemini 3.1 Pro.

**Presentations:** Strategic HTML slide decks with Chart.js integration and copywriting formulas.

## Sub-skill Architecture

The design skill delegates specialized work to external skills (brand, design-system, ui-styling) while maintaining built-in scripts for logo, CIP, banners, slides, icons, and social photos. This modular approach prevents duplication while enabling comprehensive design coverage.
