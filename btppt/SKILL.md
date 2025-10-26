---
name: btppt
description: "Billtrust PowerPoint Creation - Professional presentations following Billtrust 2025 brand standards with modern design patterns, precise color schemes, and optimized layouts for executive audiences"
license: Internal Billtrust Use Only
---

# BTPPT - Billtrust PowerPoint Creation Skill

## Overview

This skill provides comprehensive guidance for creating professional PowerPoint presentations that align with Billtrust's 2025 brand standards.

**CRITICAL**: Always read `/mnt/skills/public/pptx/SKILL.md` first to understand the technical workflow.

## Billtrust Brand Identity

### Color Palette
**Primary:** #001820 (dk teal), #FFFFFF (white), #006E53 (teal), #E7EDED (lt gray)
**Accents:** #17FF9B (neon green - signature), #4934BA (purple), #B79BFF (lt purple), #0054B3 (blue), #47C5FF (sky blue), #004C51 (dk teal)

### Typography
**Headers:** Aptos Display (bold) | **Body:** Aptos | **Fallback:** Calibri/Arial
**Sizes:** Title:54pt, Section:40pt, Content:32pt, Body:14-18pt, Small:9-11pt

### Dimensions
16:9 aspect ratio, 960px × 540px for HTML development

## Design Patterns

1. **Title Slide**: Purple gradient background, left-aligned title
2. **Section Divider**: Solid purple/teal, large white text  
3. **Content Standard**: White background, dark text, optional neon green accent line
4. **Data/Visual Heavy**: Two-column or full-width layouts
5. **Agenda/Timeline**: Bullet lists or timeline visuals

## Implementation

### Creating from Scratch (html2pptx)
1. Plan presentation outline
2. Use CSS variables from `assets/btppt-styles.css`
3. Create HTML slides (see `references/QUICKSTART.md`)
4. Convert with html2pptx
5. Validate with thumbnails

### Using Templates
See `references/Analytics_AI_EY_Content_Compressed.pptx` for real examples

## Best Practices

- **Titles**: Be specific, action-oriented, 5-8 words max
- **Body**: 3-5 bullets per slide, 10-15 words each
- **Data Viz**: One key insight per visual, use accent colors
- **Accessibility**: High contrast, dark text on light, white on dark

## Quality Checklist

✓ Colors match Billtrust 2025 palette
✓ Aptos fonts used throughout  
✓ Logo on relevant slides
✓ No text cutoff or overlap
✓ High contrast text/background
✓ 16:9 aspect ratio

## Resources

- **assets/btppt-styles.css**: Complete CSS variables
- **references/QUICKSTART.md**: Working code examples
- **references/Analytics_AI_EY_Content_Compressed.pptx**: Real presentation example

---

**Version 1.0** | January 2025 | Based on Analytics_AI_EY_Content.pptx
