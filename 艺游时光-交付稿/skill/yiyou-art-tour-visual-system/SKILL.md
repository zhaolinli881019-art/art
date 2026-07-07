---
name: yiyou-art-tour-visual-system
description: Use when creating or revising the 艺游时光 / Art Tour Time intangible cultural heritage website or similar black-white editorial cultural pages. Applies to UI direction, page rhythm, typography, logo watermark usage, bilingual Chinese-English copy treatment, and non-heritage-registration cultural operation system pages.
---

# 艺游时光 Visual System

## Use This Skill When

Use this skill for pages, sections, or Figma/web revisions for `艺游时光` with a theme of 非遗传统文化, modern art, cultural operation, public culture scenes, or bilingual black-white editorial presentation.

## Core Direction

- Overall style: black-white editorial, Behance portfolio feel, not a generic SaaS dashboard.
- Avoid heavy cards and obvious module borders unless the user asks.
- Prefer full-screen sections with strong contrast: black page, white page, black page rhythm.
- Use large Chinese headlines, small spaced English subtitles, and minimal supporting text.
- Logo should never appear as a white rectangular pasted image. Use transparent PNG or watermark treatment.

## Typography

- Chinese titles: large, calm, art-poster style; use tight but readable line-height around `1` to `1.12`.
- English subtitles: match the `Modern Art Collision` style: small uppercase, high letter spacing, medium-bold.
- Use English sparingly as atmosphere and structure, not as long explanation.
- When user asks for 繁体, convert only requested phrases unless they request the whole page.

## Page Patterns

### Hero

- Black background.
- Main title near lower half.
- `ART TOUR TIME` and `非遗工坊 / 广告策划 / 空间运营` can sit as two compact lines above the title.
- Logo may appear as low-opacity oversized watermark.

### Concept Page

- White background.
- Left: large title.
- Right: philosophical narrative text.
- Add English keywords under the title only when useful, close to the English subtitle.

### Dragon Watermark Page

- Black background.
- Center the dragon as a pale gold or white low-opacity watermark.
- Motion should be slow and subtle: breathe, slight float, slight opacity shift.

### Module Page

- Black background.
- Left title, right three rows.
- Keep original row structure: number / Chinese module title / explanatory text.
- If adding English labels, place them under the corresponding Chinese module title without disturbing the row text.

### Course Page

- White background.
- Title: `非遺绘卷 / 千年技藝歸於自然` when requested.
- Course items can be arranged as balanced rows; keep alignment and rhythm clean.
- Footer microcopy may include `讲解｜准备｜手作｜展示` with logo centered below.

### Scene Page

- Black background.
- Left: title.
- Right: circular scene elements.
- Use black/white circular badges with small English labels and subtle internal line/mark decorations.
- Avoid adding extra categories if they make the page crowded or gimmicky.

### Final Page

- White background unless user asks otherwise.
- Center/left logo with closing statement.
- Footer, if used, should be subtle on the same background unless explicitly black.

## Copy Conventions

- Brand title: `艺游时光` / `ART TOUR TIME`.
- Navigation labels used in current draft: `道`, `浮世`, `非遗绘卷`, `一隅`.
- Current hero title: `非物質文化 遺產 / Modern Art Collision / 現代藝術 碰撞`.
- Keep user-specified spacing, simplified/traditional mix, and punctuation exactly when they correct it.

## Implementation Notes

- For local preview, use a static `index.html`, `styles.css`, and `assets/` folder.
- Use transparent logo assets. If source has white background, remove it and save PNG.
- Keep assets local and referenced relatively, e.g. `./assets/yiyou-logo-transparent.png`.
- When iterating, make the smallest possible change and preserve existing page structure unless the user asks for redesign.

## Validation Checklist

- Logo has no visible white box.
- Requested page only changed where user asked.
- Black/white contrast remains readable.
- Chinese line breaks match the user’s requested line breaks.
- Navigation and footer text are not accidentally changed.
- Preview locally before reporting the URL or final files.
