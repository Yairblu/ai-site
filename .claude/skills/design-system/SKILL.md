# Design System Overview

The **ckm:design-system** is a comprehensive toolkit for creating systematic, brand-compliant design implementations.

## Core Capabilities

**Token Architecture**: A three-layer structure organizing design values from raw primitives through semantic aliases to component-specific tokens. This "enables theme switching (light/dark)" and per-component customization.

**Component Specifications**: Standardized patterns defining visual states (default, hover, active, disabled) across properties like background, text, borders, and shadows.

**Slide Generation System**: A contextual decision engine that creates persuasive presentations using:
- BM25 search across slide templates
- CSV-driven logic for layout, typography, color, and backgrounds
- Chart.js integration for data visualization
- Duarte Sparkline pattern-breaking for emotional engagement

## Key Requirements

All implementations must adhere to strict standards:
- "Use CSS variables: `var(--color-primary)`, `var(--slide-bg)`, etc."
- Import centralized token files rather than hardcoding values
- Validate compliance before deployment

## Primary Use Cases

Design token creation, component state definitions, CSS variable systems, spacing/typography scales, design-to-code handoffs, Tailwind configuration, and systematic presentation generation.

**Skill Dependencies**: Brand systems and UI styling expertise recommended for optimal implementation.
