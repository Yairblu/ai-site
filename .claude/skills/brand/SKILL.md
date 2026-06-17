# Brand Kit Documentation Overview

This documentation describes the **ckm:brand** kit—a comprehensive system for managing brand identity, voice, messaging, and visual assets.

## Core Capabilities

The kit addresses five primary areas:

1. **Voice & Messaging** – Define content tone and create messaging frameworks
2. **Visual Identity** – Establish style guides, color palettes, and typography standards
3. **Asset Management** – Organize, validate, and approve branded materials
4. **Consistency** – Audit brand compliance across touchpoints
5. **Design Systems** – Sync brand guidelines to tokens and CSS variables

## Key Workflows

The documentation outlines a "Brand Sync Workflow" that treats `docs/brand-guidelines.md` as the authoritative source, then propagates those standards to design tokens and CSS variables through automation scripts.

## Available Resources

The kit provides reference materials spanning logo usage rules, approval checklists, voice frameworks, and asset organization guidelines. Four utility scripts handle context injection, token synchronization, asset validation, and color extraction/comparison.

## Primary Entry Point

Users activate the kit by specifying actions like `[update|review|create]` followed by relevant arguments, with an optional `--json` flag for structured output formats.
